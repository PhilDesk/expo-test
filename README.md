# Première exposition
<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

Ceci est une expo test avec Juncture et le carré de sable IIIF

<param ve-config 
       title="Mon exposition test"
       author="BLRCS"
       banner="https://iiif.juncture-digital.org/banner/?url=https://upload.wikimedia.org/wikipedia/commons/b/b2/Inferno_Canto_5_line_4_Minos.jpg"
       layout="vertical">
      <!-- banner="https://iiif.juncture-digital.org/banner/?url=https://upload.wikimedia.org/wikipedia/commons/4/47/Bartholomeus_Johannes_van_Hove%2C_Het_Mauritshuis_te_Den_Haag.jpg" -->


<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->

## Anna Atkins
Publiées entre 1843 et 1853 sous forme de douze petits fascicules d'une cinquantaine de pages chacun, les Photographs of British Algae sont l'une des productions clés de l'histoire de la photographie, mariant pour la première fois photographie et édition à une époque où les livres illustrés l'étaient à la main par des dessinateurs et des graveurs. Les cyanotypes ― procédé de photographie monochrome mis au point en 1842 par John Herschel ― d'Anna Atkins forment un herbier conçu comme accompagnement du Manual of the British Marine Algae de William Harvey, qui proposait en 1841 une classification des algues à la précision et à l'ampleur inédites.[^1]

<param ve-image fit="contain"
       label="Chordaria d'Anna Atkins"
       description="Chordaria, p. 95" 
       license="public domain"
       url="https://oncs.bib.umontreal.ca/BLRCS/Chordaria_Atkins_p95.tif">

## Molière
Jean-Baptiste Poquelin, dit Molière, est un comédien et dramaturge français, baptisé le 15 janvier 1622 à Paris, où il est mort après avoir joué sur scène la quatrième représentation de sa pièce [Le Malade imaginaire](https://fr.wikipedia.org/wiki/Le_Malade_imaginaire), le 17 février 1673. 
<param ve-image fit="contain"
       label="Jean-Baptiste Poquelin, dit Molière" 
       description="Portrait de Molière" 
       license="public domain" 
       url="https://oncs.bib.umontreal.ca/BLRCS/Portrait_de_moliere.tif">
       
L'œuvre de <span data-mouseover-image-zoomto="741,600,1268,1077">Molière</span>, une trentaine de comédies en vers ou en prose, accompagnées ou non d'entrées de ballet et de musique, constitue un des piliers de l'enseignement littéraire en France. Elle continue de remporter un vif succès en France et dans le monde entier, et reste l'une des références de la littérature universelle.
<param ve-image region="164,448,2629,2232"
       label="Jean-Baptiste Poquelin, dit Molière" 
       description="Portrait de Molière" 
       license="public domain" 
       url="https://oncs.bib.umontreal.ca/BLRCS/Portrait_de_moliere.tif">

## Université de Montréal
L'Université de Montréal (UdeM) est une université publique canadienne du Québec. Elle est l'un des sept établissements d'enseignement supérieur ayant leur siège social à Montréal4, ainsi que l'une des cinq grandes universités du Canada et la deuxième en nombre d'étudiants.
<param ve-map center="41.893,12.483" zoom="10">
<!--<param ve-map center="Q36600" zoom="11" prefer-geojson>-->

<!--## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">-->

# References

[^1]: [Photographs of British Algae: Cyanotype Impressions 1843–53](https://www.metmuseum.org/art/collection/search/286656)
