<h1>Overlay Bootstrap, simple extension for Bootstrap</h1>

<h2>What is Overlay Bootstrap?</h2>

<p>Just a simple extension who add a new functionality to Bootstrap which consist to display an overlay over the Bootstrap's panel body with cool animation. No need to add new rules in a css's files, you only have to add a new class on your div! </p>

<h2>Installation</h2>

Add in the head of your file (after Bootstrap's file) the overlay-bootstrap.css or overlay-bootstrap.min.css.

<h2>Functionalities</h2>

By default, Overlay Bootstrap contains 6 different's styles and 4 display's settings.

6 styles for the 6 Bootstrap's panels:

-Default
-Primary
-Success
-Warning
-Danger
-Info

4 display's settings:

-Top to bottom (down in Overlay Bootstrap)
-Bottom to top (up in Overlay Bootstrap)
-Left to right (left in Overlay Bootstrap)
-Right to left (right in Overlay Bootstrap)

<h2>How to use Overlay Bootstrap?</h2>

In your panel body, add a new class with the style and the animation desiring.

Example:

<code>
    <div class="panel-body">
        <p>Example</p>
        
        // An right to left primary's style overlay
        
        <div class="panel-primary-overlay-right">
            <p>Your Overlay!</p>
        </div>
    </div>
    
    // Or a top to bottom danger's style overlay
    <div class="panel-body">
        <p>Example 2</p>
        
        <div class="panel-danger-overlay-down">
            <p>Your Overlay!</p>
        </div>
    </div>
</code>

