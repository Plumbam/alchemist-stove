<div align="center">

<img src="renders/angle-1.png" alt="Алхимическая печь" width="512">

# Алхимическая печь

**Стилизованная сцена в Blender: медная печь, колба с зельем, череп, свечи и свитки на старом верстаке.**

<img src="https://img.shields.io/badge/Blender-E87D0D?style=flat-square&logo=blender&logoColor=white" alt="Blender"> <img src="https://img.shields.io/badge/Cycles-3D3D3D?style=flat-square" alt="Cycles"> <img src="https://img.shields.io/badge/процедурные_материалы-5A4632?style=flat-square" alt="Процедурные материалы">

<a href="../../releases/latest"><img src="https://img.shields.io/badge/⬇_Скачать_.blend-000000?style=for-the-badge" alt="Скачать .blend"></a>

</div>

## Рендеры

Три ракурса, у каждого два варианта.

<table>
<tr>
<td align="center"><img src="renders/angle-1.png" width="256"><br><sub>Крупный план</sub></td>
<td align="center"><img src="renders/angle-1-alt.png" width="256"><br><sub>Крупный план, вариант</sub></td>
</tr>
<tr>
<td align="center"><img src="renders/three-quarter.png" width="256"><br><sub>Три четверти</sub></td>
<td align="center"><img src="renders/three-quarter-alt.png" width="256"><br><sub>Три четверти, вариант</sub></td>
</tr>
<tr>
<td align="center"><img src="renders/front.png" width="256"><br><sub>Анфас</sub></td>
<td align="center"><img src="renders/front-alt.png" width="256"><br><sub>Анфас, вариант</sub></td>
</tr>
</table>

## Что в сцене

| | |
|---|---|
| **Объекты** | медная печка с окошками, стеклянная колба с жидкостью на подставке, череп, три свечи с фитилями, свитки пергамента, верстак и полка |
| **Геометрия** | около 38,7 тыс. треугольников; Subdivision, Solidify, Mirror и Geometry Nodes |
| **Свитки** | NURBS-кривые |
| **Материалы** | медь с патиной, воск, пергамент, стекло, жидкость, дерево. Процедурные, на Noise, Wave и Voronoi |
| **Свет** | Sun + Area, светящиеся окошки печки и пламя свечей (Emission) |
| **Рендер** | Cycles, 512 × 512 |

## Файл сцены

Исходный `.blend` весит около 270 МБ, поэтому лежит не в репозитории, а в [релизе](../../releases/latest) zip-архивом (~42 МБ).

Сохранён в Blender 5.0 (предрелизная сборка 4.5.90), открывается в 5.0 и новее. Текстура грязи (`grunge_14.png`) упакована внутрь файла. Текстура печки (`текстура печки 2.png`) в файл не упакована: без неё Blender покажет печку розовой.
