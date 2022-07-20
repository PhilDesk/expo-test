# expo-test
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

# Sample visual essay

This is a sample visual essay demonstrating a few key features of a Visual Essay. Additional [Documentation](https://github.com/JSTOR-Labs/juncture/wiki) and [examples](https://jstor-labs.github.io/juncture-examples) are available for reference.
<param ve-image 
       manifest="https://oncs.bib.umontreal.ca/generateur/BLRCS/Chordaria_Atkins_p95.tif.json">

# Basic usage

## Image

Publiées entre 1843 et 1853 sous forme de douze petits fascicules d'une cinquantaine de pages chacun, les Photographs of British Algae sont l'une des productions clés de l'histoire de la photographie, mariant pour la première fois photographie et édition à une époque où les livres illustrés l'étaient à la main par des dessinateurs et des graveurs. Les cyanotypes ― procédé de photographie monochrome mis au point en 1842 par John Herschel ― d'Anna Atkins forment un herbier conçu comme accompagnement du Manual of the British Marine Algae de William Harvey, qui proposait en 1841 une classification des algues à la précision et à l'ampleur inédites.
<param ve-image 
       label="Chordaria d'Anna Atkins" 
       description="Chordaria, p. 95" 
       license="public domain" 
       manifest="https://oncs.bib.umontreal.ca/generateur/BLRCS/Chordaria_Atkins_p95.tif.json">

## Map

The work has been in the collection of the Mauritshuis in The Hague since 1902 and has been the subject of various 
literary treatments. In 2006, the Dutch public selected it as the most beautiful painting in the Netherlands.
<param ve-map center="Q36600" zoom="11" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

# References

[^1]: [Wikipedia: Girl with a Pearl Earring](https://en.wikipedia.org/wiki/Girl_with_a_Pearl_Earring)
