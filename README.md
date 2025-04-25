## Introduction: Sixteenth to Eighteenth Century Spanish Connections at Middle Temple
This exhibition celebrates Middle Temple Library’s significant collection of sixteenth and seventeenth century books published in Spain, and includes some items from the Inn’s Archive on the War of the Spanish Succession of 1701-1714. Some of the caption cards were written by Nicholas Ricardo, one of our 2024 work experience students. We are very grateful to Ana Sáez-Hidalgo (Universidad de Valladolid) for proofreading the captions, and correcting our errors. 
<br><br>
Relations between Spain and England in the late sixteenth and early seventeenth centuries were fractious and complex, mostly due to the Protestant and Catholic religious tensions between the two nations. The Anglo-Spanish War (1585-1604), although never formally declared as a war, began with England's support of Dutch rebels against Spanish rule. This period saw the 1588 Spanish Armada, a failed attempt by Spain to invade England. This was followed in 1589 by the lesser known ‘Counter Armada’, when England unsuccessfully attempted to intercept Spanish ships from returning their silver hoards from the Americas, and to capture the Portuguese Azores islands, which were occupied by Spain at the time. 
<br><br>
Throughout this period, English pirates like Francis Drake and John Hawkins routinely raided Spanish ships and colonies. This was partly sanctioned by the English crown as a form of economic warfare, but with strong denials by Elizabeth I that they were in fact sanctioned. This economic warfare was grounded in the lucrative territories and trade routes in the so-called ‘New World’, resulting in English attempts to challenge Spain's dominance in the Americas.
<br><br>
Upon his succession, James VI and I sought better relations with Spain, which resulted in the 1604 Treaty of London, and an end to the Anglo-Spanish War. This was followed by attempts to arrange a marriage between Prince Charles (later Charles I) and the Spanish Infanta Maria Anna. These negotiations ultimately failed in 1623, souring relations between the two countries once again.
<br><br>
Despite the economic and military tensions, there was an active exchange of goods and culture between the two countries. Many Spanish works were translated into English during this period, and Spanish books were readily available to purchase in England. Robert Ashley (1565-1641), the founder of the Library, translated two books from Spanish: Sebastián Fox Morcillo’s <cite> De honore</cite>, and Miguel de Luna’s <cite>Verdadera historia del rey Don Rodrigo</cite>. Equally, in 1589 he translated an anti-Spanish work into English: <cite>A comparison of the English and Spanish nation: Composed by a French Gentleman against those of the League in Fraunce, which went about to perswade the king to breake his alliance with England, and to confirme it with Spaine</cite>.

# Custom CSS and JavaScript in a Juncture Essay
This example page demonstrates the some mechanisms for embedding custom CSS and Javascript.


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


