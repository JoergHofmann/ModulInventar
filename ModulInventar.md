---
author: @(Autor.name)
date: @(Monat[heute.month].MMMM) @(heute.year)
git: @(GetShortGITHash "")
...

@(Jahr = 2021)
@(Vorjahr = Jahr - 1)
@(zielformat = "html5")
@(Aufgabe("##", "Inventur und Inventar", "inventar", "fibu0001"))
