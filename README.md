# Custom CSS and JavaScript in a Juncture Essay
This example demonstrates the some mechanisms for embedding custom CSS and Javascript.


<p class='bigText' markdown>
This text is large because of inline styles assigned to a custom class. It still allows *Markdown*.
</p>
<style>
    .bigText {
        font-size: 2rem;
    }
</style>

<script>
    // This inline script will generate a console log.
    console.log("This log is generated as an example of an inline script.");
</script>

The background of the page is gray because of the custom css file in the GitHub repo.
.ve-style ./custom.css

This attached script is adding a console log.
.ve-script ./custom.js


