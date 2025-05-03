# Bitcoin Block Visualizer

Jednoduchý nástroj pro generování vizuálních reprezentací Bitcoin bloků. Vytváří stylizované zobrazení bloků s transakcemi různých velikostí pro použití v prezentacích nebo článcích. Blok má velikost 86 x 86 transakcí a vždy je 100% využitý.

## Funkce

- Generování vizualizací Bitcoin bloků o velikosti 86 x 86 transakcí
- Nastavitelná velikost hlavní transakce
- Tenké zelené mezery mezi transakcemi
- Zelené pozadí bloku
- Export do SVG formátu
- Statistiky o vygenerovaném bloku
- 100% využití bloku

## Použití

Otevřete HTML soubor v prohlížeči, nastavte požadovanou velikost hlavní transakce, klikněte na "Generovat nový blok" a stáhněte výsledek jako SVG.

## Technické detaily

Samostatný HTML soubor bez externích závislostí. Aplikace používá algoritmus pro generování bloků s transakcemi různých velikostí, přičemž největší transakce má velikost nastavenou uživatelem. Mezi transakcemi jsou tenké zelené mezery a celý blok má vždy 100% využití.

## Údržba

Při jakýchkoliv změnách v projektu vždy aktualizujte tento README.md soubor, aby dokumentace zůstala aktuální a odpovídala skutečné funkcionalitě.

## Licence

Tento projekt je licencován pod licencí MIT - viz níže pro detaily:

```
MIT License

Copyright (c) 2025

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```