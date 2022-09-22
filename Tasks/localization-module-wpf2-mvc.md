# Lokalizační modul - převedení z WPF do ASP.NET MVC

Nový samostaný projekt, cílem projektu je převést stávající modul pro lokalizace hodnto v databázi z technologie WPF do webového prostředí provotně ASP.NET Mvc (následně ASP.NET WebApi+React, není předmětem)

## Fáze projektu

1. Výběr lokalizací

2. Editační grid verze prostý text

3. Editační grid verze HTML

4. Hromadné kolírování hodnot v mřížce

5. Export do XLS (nahrazení ExcelDataReader v Lokaliazace.BL na NPOI)

6. Import z XLS (nahrazení ExcelDataReader v Lokaliazace.BL na NPOI)

## Použité technologie

- C#

- ASP.NET Mvc

- HTML, CSS, layout

- Bootstrap

- jQuery

- TiniMCE

- Benefit.Lokalizace.BL

- Git, GitHub

## Databáze

* q.benefitcz.cz, 34777

* st3_loc

* tabulka LANG_TABLE_DEF - definice lokalizačních položek



## Postup

* Založit projekt ASP.NET MVC, Bootstrap

* Referncovat Benefit.Lokalizace.BL

* Vytvořit spojení k databázi, výpis lokalizačních položek

* ...
