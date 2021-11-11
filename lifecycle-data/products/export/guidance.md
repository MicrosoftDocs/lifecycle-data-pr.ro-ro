---
title: Îndrumări în ceea ce privește exportul privind ciclul de viață
description: Îndrumări în ceea ce privește exportul de informații privind ciclul de viață al produsului
ms.date: 12/16/2020
layout: ContentPage
ms.openlocfilehash: 5e9dddbff5fac32e6d3cf8ef0943151d2dfe5e35
ms.sourcegitcommit: 6ea3221fd5475440480515f04f33988656d71748
ms.translationtype: HT
ms.contentlocale: ro-RO
ms.lasthandoff: 11/02/2021
ms.locfileid: "3546868"
---
# <a name="lifecycle-data-export-guidance"></a>Îndrumări în ceea ce privește exportul privind ciclul de viață
Acest document descrie modul de utilizare a fișierului de export al produsului.

## <a name="query-information"></a>Informații de interogare
În documentul Excel, există câmpuri care ajută la identificarea datelor populate în tabelul de produse.

### <a name="end-of-support"></a>Sfârșitul perioadei de asistență
Valoarea Sfârșitul perioadei de asistență va filtra produsele fie după data de sfârșit a perioadei de asistență a produsului, fie după data de sfârșit a lansării acestuia.

Valori posibile: Toate (nu se aplică niciun filtru), An și un Interval.

### <a name="family"></a>Familie
Valoarea familiei filtrează produsele după nivelul părinte din ierarhia cunoscută drept familie.

Valori posibile: Toate (nu se aplică niciun filtru), Nume de familie

### <a name="group"></a>Grup
Valoarea grupului filtrează produsele din nivelul părinte (familie) într-un anumit grup.

Valori posibile: Toate (nu se aplică niciun filtru), Nume de grup

## <a name="table-columns"></a>Coloane de tabel
Tabelul produsului este format din coloane care definesc produsul, edițiile, lansările și datele de asistență corespunzătoare.

> [!NOTE]
> Va apărea un rând pentru fiecare combinație de produs, ediție și lansare.

### <a name="product"></a>Produs
Numele produsului.

### <a name="edition"></a>Ediție
Coloana ediție va fi completată atunci când produsul conține ediții. Atunci când nu există nicio ediție de produs, acest câmp va fi necompletat.

### <a name="release"></a>Lansare
Coloana lansare va fi completată atunci când produsul conține mai multe lansări.
Atunci când produsul are o singură lansare, acest câmp va fi necompletat.

### <a name="support-policy"></a>Politica de asistență
Acest câmp definește politica de asistență pe care o urmează produsul.

Valori posibile: [Fixă](/lifecycle/policies/fixed), [Modernă](/lifecycle/policies/modern), Componentă

### <a name="start-date"></a>Data de începere
Data de începere a asistenței pentru produs.

### <a name="mainstream-date"></a>Data mainstream
Atunci când Politica de asistență este **Fixă** sau **Componentă**, aceasta este data de sfârșit a produsului mainstream.
  
Atunci când Politica de asistență este **Modernă**, aceasta va fi necompletată.

### <a name="extended-end-date"></a>Data de sfârșit extinsă
Atunci când Politica de asistență este **Fixă** sau **Componentă**, aceasta este data de sfârșit extinsă a produsului.

Atunci când Politica de asistență este **Modernă**, aceasta va fi necompletată.

### <a name="retirement-date"></a>Data retragerii
Atunci când Politica de asistență este **Fixă** sau **Componentă**, aceasta va fi necompletată.

Atunci când Politica de asistență este **Modernă**, aceasta va fi data de retragere a produsului.

### <a name="release-start-date"></a>Data de începere a lansării
Data la care a început asistența pentru lansare. Atunci când produsul are o singură lansare, acest câmp va fi necompletat.
 
### <a name="release-end-date"></a>Dată de sfârșit a lansării
Data la care s-a încheiat asistența pentru lansare.
Atunci când produsul are o singură lansare, acest câmp va fi necompletat.

### <a name="docs-url"></a>URL de documente
URL la documentația extinsă.
