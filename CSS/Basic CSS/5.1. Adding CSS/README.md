# CSS Style Selectors

For TAGS :

Example 1: 
h1 {
    background-color: red;
}

Example 2:
body {
    color: green !important;
}

Example 3:
img {
    align-items: center;
}

----------------------------------------------------------------

For Classes :

Example 1:
.highlight {
    border: 10px solid black;
}

Example 2:
.block {
    align-text: center;
}

Example 3:
.first {
    .color: black;
}

----------------------------------------------------------------

For IDs : (There can be only one ID, Only one element per file & ID have the max priority)

Example 1:
#main {
    thickness: 20px;
}

Example 2:
#name {
    font-weight: bold;
    font-size: 20px;
}

Example 3:
#rollno {
    align-text: center;
}

----------------------------------------------------------------

Attribule Selectors :

1- Tags
2- Classes
3- IDs
4- Draggables
5- Src
6- Href
7- Alt

We can also take this one step further by adding values to draggable attributes

Example :

HTML File :

<p draggable="true">Hi, There!</p>
<p draggable="false">Hi, There!</p>

Css File :

p[draggable] {
    color: red;
}

p[draggable="false"] {
    color: blue;
}

And you can apply some css attributes to whole file just by using '*'

Example:

CSS File :

* {
    color: yellow;
}
