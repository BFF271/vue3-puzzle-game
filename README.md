## Project name

Digital Huarong Road
[Online experience] (http://www.h5love.cn/pingtu/)

## Stack

vue3 + vite2

## How to use

```js
<num-game
:gamedata="gamedata"
ref="game"
@endCallback="endCallback"> </num-game>

```

## Configuration items

```js
{
   level: 3 , // The default is 3*3 to generate an array disk, support 3, 4, 5, 6
   mode: "number", // default 'number' supports 'number' and 'img', if mode='img' the following imgs parameter is required
   imgs:[], //Image path, need to customize the number of sheets according to the level
   style: {
     sliderBg: "red", // slider background color
     sliderColor: "#fff", // slider font color
     sliderFontSize: "14px", // slider font size
     gameBoxBg: "#5a009b", // Game board background color
   }
}
```

## API

- `game` game start
- `endCallback` game over
