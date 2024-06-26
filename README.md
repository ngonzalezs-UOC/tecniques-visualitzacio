# tecniques-visualitzacio

![img.png](banner-readme.jpg)
*[Designed by starline / Freepik](https://www.freepik.com)*

## Context

Els elements d'aquest repositori constitueixen la resposta a la PAC 2 de l'assignatura *Visualització de dades* del *Màster en Ciència de Dades* de la [Universitat Oberta de Catalunya](https://www.uoc.edu/portal/ca/index.html) (UOC), corresponent al segon semestre del curs 2023-2024.

L'objectiu és implementar una visualització de dades relacionada amb cadascuna de les tres tècniques assignades individualment pel professor de l'assignatura. Aquestes tècniques són: *Proportional Symbol Map*, *Rose Chart* i *Word Cloud* (o *Tag Cloud*).

## Accés a les visualitzacions

La visualització directa és possible a través del [Web site de Github Pages corresponent a aquest repositori](https://ngonzalezs-uoc.github.io/tecniques-visualitzacio/). Això no obstant, tot seguit també es proporcionen els enllaços individuals directes:

**Proportional Symbol Map**
- Interactiva: [ProportionalSymbolMap.html](https://ngonzalezs-uoc.github.io/tecniques-visualitzacio/ProportionalSymbolMap/output/ProportionalSymbolMap.html) 
- Imatge: [ProportionalSymbolMap.png](https://ngonzalezs-uoc.github.io/tecniques-visualitzacio/ProportionalSymbolMap/output/ProportionalSymbolMap.png) 

**Rose Chart**
- Interactiva: [RoseChart.html](https://ngonzalezs-uoc.github.io/tecniques-visualitzacio/RoseChart/output/RoseChart.html) 
- Imatge: [RoseChart.png](https://ngonzalezs-uoc.github.io/tecniques-visualitzacio/RoseChart/output/RoseChart.png) 

**Word Cloud**
- Imatge Word Cloud estàndard: [WordCloud_estandard.png](https://ngonzalezs-uoc.github.io/tecniques-visualitzacio/WordCloud/output/WordCloud_estandard.png) 
- Imatge Word Cloud emmascarat: [WordCloud_emmascarat.png](https://ngonzalezs-uoc.github.io/tecniques-visualitzacio/WordCloud/output/WordCloud_emmascarat.png) 

## Repositori

El projecte es troba en [aquest repositori públic de GitHub](https://github.com/ngonzalezs-UOC/tecniques-visualitzacio), i la seva estructura és la següent: 

```bash
────tecniques-visualitzacio
    │
    ├───ProportionalSymbolMap
    │   │     
    │   ├─── dev
    │   │        *.*
    │   └─── output
    │            ProportionalSymbolMap.*
    │
    ├───RoseChart
    │   │     
    │   ├─── dev
    │   │        *.*
    │   └─── output
    │            RoseChart.*
    │
    ├───WordCloud
    │   │     
    │   ├─── dev
    │   │        *.*
    │   └─── output
    │            WordCloud_*.*
    │
    ├─── LICENSE
    ├─── README.md
    └─── banner-readme.png 

```
- **ProportionalSymbolMap/dev/\*.\***: Codi font en Jupiter Notebook, datasets d'entrada i fitxers auxiliars.
- **ProportionalSymbolMap/output/ProportionalSymbolMap.\***: Fitxers amb les visualitzacions generades (imatges i codi html)
- **RoseChart/dev/\*.\***: Codi font en Jupiter Notebook, datasets d'entrada i fitxers auxiliars.
- **RoseChart/output/RoseChart.\***: Fitxers amb les visualitzacions generades (imatges i codi html)
- **WordCloud/dev/\*.\***: Codi font en Jupiter Notebook, datasets d'entrada i fitxers auxiliars.
- **WordCloud/output/WordCloud_\*.\***: Fitxers amb les visualitzacions generades (imatges)
- **LICENSE**: Document amb els termes de la llicència aplicada al projecte.
- **README.md**: Document explicatiu del projecte.
- **banner-readme.jpg**: Imatge (banner) incrustada a la capçalera del fitxer README.md.

## Autoria

Totes i cadascuna de les parts d'aquest treball han estat realitzades exclusivament de forma individual per **Nicolás González Soler**.

## Llicència

Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

Tots i cadascun dels continguts d'aquest projecte estan sotmesos a la llicència
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa], excepte pel que respecta als datasets emprats sobre els que caldria observar les llicències eventualment preexistents que són d'aplicació.

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
