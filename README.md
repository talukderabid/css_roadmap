# css_roadmap
# CSS
Casecading Style Sheet

It is a language that is used to describe the style of a document.

## Basic Syntax
Selector

    h1 {
        color: red;
    }

## Including Style
- Inline
    < h1 style="color:red"> Abid </ h1>

- < style> tag

    < style>
        h1 { <br>
            color: red; <br>
        }<br>
    </ style>

- External Stylesheet: <br>
Writing CSS in a separate document & linking it with HTML file.

## Color Property
Used to set the color of foregraound.

color: red;<br>
color: pink;<br>
color: blue;<br>
color: green;<br> 

## Backgroup Color Property
Used to set the color of background.

- background-color: red;

## Color System
- RGB

    color: rgb(255,0,0);<br>
    color: rgb(0,255,0);

- Hex (Hexadecimal)

    color: #ff0000;<br>
    color: #00ff00;

## Selectors
- Universal selector:<br>
*{}

- Element selector:<br>
h1 {}

- Id selector:<br>
#myid{}

- Class selector:<br>
.myClass{}