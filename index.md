---
presentation:
  width: 960
  height: 700
  minScale: 1
  maxScale: 2
  # presentation theme
  # === available themes ===
  # "beige.css"
  # "black.css"
  # "blood.css"
  # "league.css"
  # "moon.css"
  # "night.css"
  # "serif.css"
  # "simple.css"
  # "sky.css"
  # "solarized.css"
  # "white.css"
  # "none.css"
  theme: simple.css

---

<!-- slide  -->


#### Atlas numérique de la DDT 31
<img src="imgs/atlas.png" style="width:100%">


<!-- slide -->
#### Objectif

##### **Alternative au format papier**

<hr>

<div style="margin:0 auto; text-align:justify; font-size:1.8rem">

Le support numérique propose d'indéniables avantages par rapport au papier.

Il permet notamment de **sortir du carcan** des cartes statiques **figées** à l'échelle d'un département et des limites imposées par les formats de page.

L'objectif de ce projet a été de mettre à profit ces avantages pour donner à voir les données de manière plus **dynamique** et pertinente sous une forme **innovante**.
</div>
<hr>
<img src="imgs/atlas_papier_2014.png" align="center" style="max-width:50%">

<!-- slide data-background-image="imgs/photo_page_sea.jpg"data-background-size="40% 100%" data-background-position="0 0" -->
#### &nbsp;&nbsp;Méthode

<div style="margin:0 0 0 40%; text-align:left; font-size:1.8rem">

- Thématique
  - réunions avec le service concerné
    - Quelles données sont les plus pertinentes
    - Comment les obtenir
    - Comment les représenter
    
</div>

<!-- slide  -->

<div style="display:flex">
  <div>
    <h4>Aspect technique</h4>
    <div style="margin:0 10px 0 0; text-align:left; font-size:1.4rem;">L'atlas numérique de la DDT 31 est un site internet utilisant des outils libres et/ou gratuits. Il est
        développé en interne avec des **participations externes**.

  - Structure et le fonctionnement: **php** & **framework codeigniter**
  - Style & "responsive": **bootstrap 5**
  - Cartographies dynamiques: **openlayers 6**

  - Graphiques dynamiques et cartes statistiques: **HighCharts.js** 
  - Aussi utilisées pour certains graphiques et cartes: **D3.js** et **plot.js**
  - Gestionnaire de version: **Git**
    </div>

  </div>

  <div style="flex: 0 0 400px;">
    <img src="imgs/git_victor_loic.png" align="center" style="width:100%;">
  </div>

</div>


<div style="margin:0 0 0 0; text-align:left; font-size:1.4rem"></div>

<!-- slide  -->
<table>
<tr>
<td valign="middle">
<img src="imgs/photo_page_sea.jpg">
</td>
<td valign="middle">></td>
<td style="Width:50%">
  <img src="imgs/apercu_page_agri.png">
</td>
</tr>
</table>

<!-- slide  -->
<div style="text-align:left">

#### Coopérations

<div style="margin:0 0 0 0; text-align:left; font-size:1.4rem">

- Début du projet, prototype et premiers développements avec Victor Arricau.

- Travail avec Alain Roan (perceptible.fr). Améliorations et optimisations.

</div>
</div>
<!-- slide  -->

##### Extrait du travail réalisé avec `perceptible.fr`

<img src="imgs/notion_backlog_sprint_2.png">



<!-- slide  -->
<h4>Progression</h4>
<table>
<tr>
  <td valign="middle">
  <img src="imgs/agri_bad1.png" style="max-height:250px">
  </td>
  <td valign="middle">></td>
  <td style="Width:50%">
    <img src="imgs/agri_good1.png" style="max-height:250px">
  </td>
</tr>
<tr>
  <td valign="middle">
  <img src="imgs/camenbert_primrenov_bad.png" style="max-height:250px">
  </td>
  <td valign="middle">></td>
  <td style="Width:50%">
    <img src="imgs/camenbert_primrenov_good1.png" style="max-height:250px">
  </td>
</tr>


</table>


<!-- slide data-background-image="imgs/responsive_accueil.png"  -->

Le site est "responsive"


<!-- slide   -->
<div style="text-align:left">

#### Préparation des données ... Outils
- QGIS 
- Postgre / postgis
- batch, ogr
- Duckdb 

---

#### Outil spécifique: 

- GéoIDE carto (cartes en ligne, flux wms)

</div>

<!-- slide -->

<img src="imgs/goal_finish_race.svg">