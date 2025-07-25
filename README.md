# Custom CSS and JavaScript in a Juncture Essay
This example page demonstrates the some mechanisms for embedding custom CSS and Javascript.

.ve-media gh:juncture-digital/juncture/static/images/juncture-logo.png

.ve-map 42.281,-83.748 9 width=50%


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


