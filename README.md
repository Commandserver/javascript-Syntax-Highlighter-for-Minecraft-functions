# Javascript syntax highlighter for Minecraft functions
A Javascript function to highlight Minecraft functions code.

This Javascript highlighter can be used to highlight Minecraft code on your websides.
* for Minecraft 1.13 to 1.16

## How to use it

Just execute the `mclangHighlight` function and pass the minecraft command into it.

#### Example:

```javascript
document.getElementById('myElement').innerHTML = mclangHighlight("particle minecraft:barrier ~ ~42 ~ 0.4 0.5 0.4 1 6 force @a[gamemode=spectator]");
```

## Installation

to use it on your webpage you have to declare the css variables to color the code.
You can use this css code:

```css
span.selector {
    color: #05cc94;
}
span.selectorProperties {
    color: #4196b7;
}
span.not {
    color: #ff5151;
}
span.minecraft {
    color: #3c47e6;
}
span.number {
    color: #db480f;
    font-weight: bold;
}
span.bracket {
    color: #05cc94;
    font-weight: bold;
}
span.error {
    background-color: #d0320d;
    border-radius: 2px;
}
span.light-error {
    background-color: #52503a;
    border-radius: 2px;
    text-decoration: underline;
    text-decoration-style: dotted;
}
span.function {
    color: #53a600;
}
span.comment {
    color: #646363;
}
span.keyword {
    color: #e951ff;
}
span.var {
    color: #caa536;
}
```
