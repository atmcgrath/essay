# essay

<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="My Visual Essay"
       author="Alice McGrath"
       banner="https://iiif.juncture-digital.org/banner/?url=https://upload.wikimedia.org/wikipedia/commons/4/47/Bartholomeus_Johannes_van_Hove%2C_Het_Mauritshuis_te_Den_Haag.jpg" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q173223"> <!-- Mary Cassatt -->
<param ve-entity eid="Q18519125"> <!-- Portrait of an elderly lady in a bonnet: red background -->
<param ve-entity eid="Q36600"> <!-- The Hague -->
<param ve-entity title="Philadelphia" eid="Q1345" fill="#92086D">


# Sample visual essay

This is a sample visual essay demonstrating a few key features of a Visual Essay. Additional [Documentation](https://github.com/JSTOR-Labs/juncture/wiki) and [examples](https://jstor-labs.github.io/juncture-examples) are available for reference.
<param ve-image 
       url="https://triarte.brynmawr.edu/Media/images/1972.1_BMC_f.jpg">
       

# Basic usage

## Flowers

_Plant Portfolio - Iris_ by painter Alida Fish, who is not in wikidata. From Bryn Mawr College's Art and Artifacts collection: [accession number: 2006.1.287](https://triarte.brynmawr.edu/artist-maker/info/22047)
From the Scott collection of women artists. 

<param ve-image
       label="Plant Portfolio - Iris"
       description="Painting of an Iris by Alida Fish"
       license="Bryn Mawr College"
       url="https://triarte.brynmawr.edu/Media/images/2006.1.287_BMC_f_3.jpg">
       
Mr. Branghton was very angry, and scolded them violently: however, we were obliged to descend, and stools were procured for us in the shop, where we found the brother, who was highly delighted, he said, that his sisters had been catched; and he thought proper to entertain me with a long account of their tediousness, and the many quarrels they all had together.

## Epistolary narratives

I have more to say about this example of letter writing.
<param ve-image 
       url="https://triarte.brynmawr.edu/Media/images/1972.1_BMC_f.jpg">

When, at length, these ladies were equipped to their satisfaction, they made their appearance; but before any conversation was suffered to pass between them and us, they had a long and most disagreeable dialogue with their father, to whose reprimands, though so justly incurred, they replied with the utmost pertness while their brother all the time laughed aloud.

The moment they perceived this, they were so much provoked, that, instead of making any apologies to Madame Duval, they next began to quarrel with him. "Tom, what do you laugh for? I wonder what business you have to be always a laughing when Papa scolds us?"

<param ve-image 
       url="https://triarte.brynmawr.edu/Media/images/1972.1_BMC_f.jpg">

## Map

This sort of dialogue we were amused with till dinner was ready, when we again mounted up two pairs of stairs.

In our way, Miss Polly told me that her sister had asked Mr. Smith for his room to dine in, but he had refused to lend it; "because," she said, "one day it happened to be a little greased: however, we shall have it to drink tea in, and then, perhaps, you may see him; and I assure you he's quite like one of the quality, and dresses as fine, and goes to balls and dances, and every thing, quite in taste; and besides, Miss, he keeps a foot-boy of his own too."

<param ve-entity title="Philadelphia" eid="Q1345" fill="#92086D">
<param ve-map center="Q1345" zoom="11" prefer-geojson marker-type="circle">
<param ve-map-layer geojson active url="https://digitalscholarship.brynmawr.edu/livingcampus/lc-data.geojson" title="Plants on Campus">


## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.

The dinner was ill-served, ill-cooked, and ill-managed. The maid who waited had so often to go down stairs for something that was forgotten, that the Branghtons were perpetually obliged to rise from table themselves, to get plates, knives, and forks, bread or beer. Had they been without pretensions, all this would have seemed of no consequence; but they aimed at appearing to advantage, and even fancied they succeeded. However, the most disagreeable part of our fare was that the whole family continually disputed whose turn it was to rise, and whose to be allowed to sit still.

<param ve-image 
       url="https://www.wikidata.org/wiki/Q18519125#/media/File:Portrait_of_an_Elderly_Lady_in_a_Bonnet_-_Red_Background_by_Mary_Cassatt.jpg">
<param ve-map center="Q1345" zoom="11" prefer-geojson marker-type="circle">

# References

