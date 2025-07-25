# Custom CSS and JavaScript in a Juncture Essay
This example page demonstrates the some mechanisms for embedding custom CSS and Javascript.

.ve-media gh:juncture-digital/juncture/static/images/juncture-logo.png

.ve-map Q93195 9 right sticky
	- Q10686
	- Q1761

MacMasters recounts... "The Linen Board, created by the Irish Parliament in 1711, further subsidized the flax growers by importing and distributing flaxseed (MacMasters, 2009, as cited in Gribbon, 1977)." [^4]  "Being determined to give Encouragement for the raising large Quantities of Flax in this Kingdonm,  the "Trustees of the Linnen Manufacture" offered five bushels of foreign seed for every acre contracted to be sown in flax (MacMaster, 2009  as cited in the Dublin Currant, 1723)." [^5]  "From the first the Board also paid bounties and premiums for high quality linen, supplied wheels and looms, and made grants for bleach greens and manufactories (MacMaster, 2009, p.15, as cited by McConaghy, 1979)." [^6]   "The board eventualy required recipiants to returen twice as much seed as they had received" (Macmaster, 2009 p16). Flax growers in Ireland traditionally sourced quality flax seed from the Baltic in areas such as Riga, Latvia but American colonists soon developed quality seed to compliment this market.  "Flaxseed exports, which were shipped only to Ireland, rose steadily and became Pennsylvania's, third most impoirtant export after flour and bread, the staples of Philadelphias European and West Indian trade (MacMaster, 2009 p.69 as cited by Engal, 1974)." [^7] 


Merchants in America coordinated this new colonial flax seed export.  "Hugh Davey and Samuel Carson, and several others, had established a base at Charlestown, Cecil County, Maryland where they could purchase wheat, flour & flaxseed " (MacMaster, 2009 p201 as cited by Johnston, 1881). [^8]   "From 1745-1750 Davey & Carson, merchants of falxseed, flour, wheat, rum and general dry goods, documented shipments of flaxseed in hogsheads in their letterbook correspondence." [^9]. This Maryland location was in close proximity to Pennsylvania trading centers in areas such as Philadelphia, Carlisle and Lancaster providng a gateway for trade and commerce. Development in infrastructure such as the Pennsylvania and Forbes Road further enabled trade between the eastern and western parts of the Pennsylvania colony [^10] .
{enter=flyto:Q180402}



Flax was transported in a large cask or barrel typically made of wood called "hogshead" a term for a unit of measurement [^11].  "Since a hogshead contained seven bushels of seed,  Philadelphia shipped roughly 3000 hogshead in 1749, 6000 in 1750 and 10,000 in 1751." (MacMaster, 2009 p69-70 as cited by White). [^12]   "With the increase of imports of American flaxseed to Ireland, and Irish linen to the colonies, advertisements in the Belfast News Letter, the only newspaper in the north for ships sailing for New Castle, Philadelphia or New York comonly extolled the ships advantages for passengers, redemptioners and servants" (MacMaster, 2009 p70).  "Immigrants from Ireland especially Ulster whether free, bond servant or slave, supported the flax seed and textile trade. Poorer weavers and cotters financed their crossing by depending on family or friends in America to pay their passage or by selling their labour as servants.  Between the years 1768-72, shipowners hauled 233,065 bushels of flax, becoming the single most important export to Ireland.  In the eighteenth century the domestic linen industry expanded from annual exports of less than one million to forty million yards of cloth." (MacMaster, 2009 p.ix). "With expences adjusted, shipping earnimgs for flax was more profitable than the tobacco trade" (MacMaster, 2009. p.285).  



<p class='smallText' markdown>
This text is small because of inline styles assigned to a custom class in a wrapper paragraph element that will only be visible in a code editor. It still allows *Markdown*.
</p>

<style>
    .smallText {
        font-size: .75rem;
    }
</style>

The background of the page is gray because of the custom css file in the GitHub repo.

.ve-style ./custom.css

An inline script is adding a console log.

<script>
    // This inline script will generate a console log.
    console.log("This log is generated as an example of an inline script.");
</script>


And an attached script is adding another.

.ve-script ./custom.js


