#Overlay Bootstrap, simple extension for Bootstrap#

Demo : http://karbonn.github.io/Overlay-Bootstrap/

## What is Overlay Bootstrap? ##

Just a simple extension who add a new functionality to Bootstrap which consist to display an overlay over the Bootstrap's panel body with cool animation. No need to add new rules in a css's files, you only have to add a new class on your div!

You can also add a cool caption on your images!

## Installation ##

Add in the head of your file (after Bootstrap's file) the overlay-bootstrap.css or overlay-bootstrap.min.css.

## Functionalities ##

By default, Overlay Bootstrap contains 6 differents styles and 4 displays settings.

### Overlay: ###

**6 styles for the 6 Bootstrap's panels:**

- Default
- Primary
- Success
- Warning
- Danger
- Info

#### 4 displays settings: ####

- Top to bottom (down in Overlay Bootstrap)
- Bottom to top (up in Overlay Bootstrap)
- Left to right (left in Overlay Bootstrap)
- Right to left (right in Overlay Bootstrap)

### Caption: ###

#### 5 displays settings: ####

- Bottom to top (up in Overlay Bootstrap) 
- Top to bottom (down in Overlay Bootstrap) 
- Left to right (right in Overlay Bootstrap) 
- Right to left (left in Overlay Bootstrap)
- Half-down | half-up

### NEW: Animated Progress bars! ###

## How to use Overlay Bootstrap? ##

Overlay:
In your panel body, add a new class with the style and the animation desiring.

Caption:
In your caption's class, you only have to add an id with the effect desiring: id="caption-right" or id="caption-top".

Example:

```
    <div class="panel-body">
        <p>Example</p>
        
         An right to left primary's style overlay
        
        <div class="panel-primary-overlay-right">
            <p>Your Overlay!</p>
        </div>
    </div>
```
    
Or a top to bottom danger's style overlay
```
    <div class="panel-body">
        <p>Example 2</p>
        
        <div class="panel-danger-overlay-down">
            <p>Your Overlay!</p>
        </div>
    </div>
```
    
Caption on image

```
    <div class="thumbnail">
    
    <img src="..." alt="image"  />
```
    
For a bottom to top caption
    
```
    
        <div class="caption caption-up">
        
         <h3>Thumbnail label</h3>
         <p>Some sample text. </p>
         <p>
            <a href="#" class="btn btn-primary" role="button">
               Button
            </a> 
            <a href="#" class="btn btn-default" role="button">
               Button
            </a>
         </p>
    </div>
    
    </div>
    
    <div class="thumbnail">
    <img src="..." alt="image"  />
```

For a left to right caption
    
```
   
    <div class="caption caption-right">
         <h3>Thumbnail label</h3>
         <p>Some sample text. </p>
         <p>
            <a href="#" class="btn btn-primary" role="button">
               Button
            </a> 
            <a href="#" class="btn btn-default" role="button">
               Button
            </a>
         </p>
    </div>
    </div>
```
For half-up and half-down
    
    ```
        <div class="caption caption-half-down">
            Overlay Down
        </div>
        <div class="caption caption-half-up">
            Overlay Up
        </div>
    </div>

## Licence ##
The MIT License (MIT)

Copyright (c) 2016 

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.