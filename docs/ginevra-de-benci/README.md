<a href="https://dev.visual-essays.app"><img src="https://dev-visual-essays.netlify.app/images/ve-button.png"></a>

<param ve-config 
       banner="https://free.iiifhosting.com/iiif/a50b36d92153db8db436cff50ab37345ad482823e756d48585829e9a20cdc2c3/pct:0,52,100,38/full/0/default.jpg" 
       layout="vtl" 
       title="Ginevra de' Benci" 
       author="Leonardo da Vinci">

# IIIF usage examples

## Ginevra de' Benci
 
<param ve-entity title="Florence" eid="Q2044" aliases="florentine">
<param ve-entity title="Ginevra de' Benci" eid="Q3494135">
<param ve-entity title="Leonardo da Vinci" eid="Q762">

<param ve-image primary manifest="https://jstor-labs.github.io/iiif/manifests/Ginevra_de_Benci-labs.json">

<span eid="Q1267893">Ginevra de' Benci</span> is a portrait painting by Leonardo da Vinci of the 15th-century Florentine aristocrat <span eid="Q3494135">Ginevra de' Benci</span> (born c.  1458).[^1] The oil-on-wood portrait was acquired by the National Gallery of Art in Washington, D.C. in 1967. The sum of US$5 million—an absolute record price at the time—came from the Ailsa Mellon Bruce Fund and was paid to the Princely Family of Liechtenstein. It is the only <span data-mouseover-image-zoomto="f5e620db">painting</span> by Leonardo on public view in the Americas.[^2]

Ginevra de' Benci, a well-known young Florentine woman, is universally considered to be the portrait's sitter. Leonardo painted the portrait in <span data-click-map-flyto="43.77,11.253,12">Florence</span> between 1474 and 1478, possibly to commemorate Ginevra's marriage to Luigi di Bernardo Niccolini at the age of 16. More likely, it commemorates the engagement. Commonly, contemporary portraits of females were commissioned for either of two occasions: betrothal or marriage. Wedding portraits traditionally were created in pairs, with the woman on the right, facing left; since this portrait faces right, it more likely represents betrothal.[^3]
<param ve-map prefer-geojson center="Q2044" zoom="7" basemap="Stamen_TerrainBackground">

The <span data-mouseover-image-zoomto="6642,307,2220,3721">juniper bush</span> that surrounds Ginevra's head and fills much of the background, serves more than mere decorative purposes. In <span data-click-image-zoomto="7183,6142,2259,3101">Renaissance Italy</span>, the juniper was regarded a symbol of female virtue, while the Italian word for juniper, ginepro, also makes a play on Ginevra's name.[^4] The imagery and text on the reverse of the panel further support the identification of this picture. The reverse is decorated with a juniper sprig encircled by a wreath of laurel and palm and is memorialized by the phrase Virtvtem Forma Decorat ("Virtue Adorns Beauty").
<param ve-image manifest="Ginerva_de_Benci-reverse.json">

The Latin motto Virtvtem Forma Decorat on the reverse of the portrait, is understood as symbolizing the intricate relationship between Ginevra's intellectual and moral virtue on the one hand, and her physical beauty on the other. The sprig of juniper, encircled by laurel and palm, suggests her name. The laurel and palm are in the personal emblem of Bernardo Bembo, a Venetian ambassador to Florence whose platonic relationship with Ginevra is revealed in poems exchanged between them. Infrared examination has revealed Bembo's motto "Virtue and Honor" beneath Ginevra's, making it likely that Bembo was somehow involved in the commission of the portrait.
 <param ve-image iiif manifest="Ginevra_de_Benci-reverse.json">

The portrait is one of the highlights of the National Gallery of Art, and is admired by many for its portrayal of Ginevra's temperament. Ginevra is beautiful, but austere; she has no hint of a smile and her gaze, although forward, seems indifferent to the viewer.[^5]
<param ve-image manifest="Ginevra_de_Benci-iiifhosting.json" region="pct:40,40,20,20">

At some point, the bottom of the painting was removed, presumably owing to damage, and Ginevra's arms and hands are thought to have been lost.[^6] Using the golden section, Susan Dorothea White has drawn [an interpretation](http://www.susandwhite.com.au/enlarge.php?workID=162) of how her arms and hands may have been positioned in the original.[^7] The adaptation is based on drawings of hands by Leonardo thought to be studies for this painting.

## External manifests

This paragraph provide an example of using external manifest in a visual essay.  Librarys, museums and other content sites often use IIIF to view content images online and sometimes provide a link to the IIIF manifests.  In this example we're using a manifest from the National Gallery of Art.  Wellcome Library.
<param ve-image primary manifest="https://www.nga.gov/api/v1/iiif/presentation/manifest.json?cultObj:id=50724">

Here's another example using an external IIF manifest.  This manifest URL was found on the Wellcome Library website. 
<param ve-image manifest="https://wellcomelibrary.org/iiif/b18035723/manifest?manifest=https://wellcomelibrary.org/iiif/b18035723/manifest">


## Single image from manifest

Manifests can often include may individual images.  In this example we use a specific image using the `seq` attribute.
<param ve-image 
       manifest="https://iiif.lib.harvard.edu/manifests/drs:459932907"
       seq="143"
       rotate="90">

## References

[^1]: "Ginevra de' Benci". National Gallery of Art. D.C. Retrieved 16 November 2014.
[^2]: "Leonardo da Vinci's Ginevra de' Benci" Archived 21 December 2005 at the Wayback Machine National Gallery of Art. Washington, D.C. Retrieved 5 June 2013.
[^3]: "Ginevra de' Benci [obverse]". National Gallery of Art. Retrieved 16 April 2019.
[^4]: Bacci, Mina (1978) [1963]. The Great Artists: Da Vinci. Translated by Tanguy, J. New York: Funk & Wagnalls.
[^5]: Brown (2003)
[^6]: Wallace, Robert (1966). The World of Leonardo: 1452–1519. New York: Time-Life Books. p. 48.
[^7]: White, Susan D. (2006). Draw Like Da Vinci. London: Cassell Illustrated. ISBN 9781844034444, pp.114-115.
