# javascript-Syntax-Highlighter-for-Minecraft-functions
A Javascript function to highlight Minecraft functions code

## How to use it

Just execute the function and pass the minecraft command into it.

## Example

```javascript
document.getElementById('myElement').innerHTML = highlight("particle minecraft:barrier ~ ~42 ~ 0.4 0.5 0.4 1 6 force @a[gamemode=spectator]");
```

## Installation

to use it on your webpage you have to declare the css variables to color the code.
You can use this css code:

```css
.selector {
  color: #027102;
}
.selectorProperties {
  color: #00ccff;
}
.not {
  color: #ff5151;
}
.minecraft {
  color: #3c47e6;
}
.score {
  color: #c86904;
}
.number {
  color: #f43408;
  font-weight: bold;
}
.bracket {
  color: #53a600;
  font-weight: bold;
}
.error {
  background-color: #d0320d;
}
.function {
  color: #53a600;
}
```
