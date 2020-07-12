# Javascript syntax highlighter for Minecraft functions
A Javascript function to highlight Minecraft functions code
* for Minecraft 1.13 to 1.16

## How to use it

Just execute the function and pass the minecraft command into it.

## Example

```javascript
document.getElementById('myElement').innerHTML = mclangHighlight("particle minecraft:barrier ~ ~42 ~ 0.4 0.5 0.4 1 6 force @a[gamemode=spectator]");
```

## Installation

to use it on your webpage you have to declare the css variables to color the code.
You can use this css code:

```css
.selector {
    color: #05cc94;
}
.selectorProperties {
    color: #4196b7;
}
.not {
    color: #ff5151;
}
.minecraft {
    color: #3c47e6;
}
.number {
    color: #db480f;
    font-weight: bold;
}
.bracket {
    color: #05cc94;
    font-weight: bold;
}
.error {
    background-color: #d0320d;
    border-radius: 2px;
}
.function {
    color: #53a600;
}
.comment {
    color: #646363;
}
.keyword {
    color: #e951ff;
}
.var {
    color: #caa536;
}
```
