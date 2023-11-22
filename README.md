<h1 align="center">Welcome to class-to-style 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-0.0.0-blue.svg?cacheSeconds=2592000" />
  <a href="https://twitter.com/tsaowe" target="_blank">
    <img alt="Twitter: tsaowe" src="https://img.shields.io/twitter/follow/tsaowe.svg?style=social" />
  </a>
</p>

> You can just use class to style your html element, It's very easy but powerful.
> 
```html


<div class="margin-20-30">
  <div class="width-50 height-50">
    <div class="rotate-90-deg font-12-regular">this div will rotate 90 deg</div>
  </div>
</div>

```


## Install

```sh
yarn add class-to-style
// or
npm install class-to-style

// usage
import 'class-to-style/dist/class-to-style.min.css'


```

### Support css
<table>
<thead>
<tr>
<td width="250">class name</td>
<td >min value</td>
<td >max value</td>
<td >step</td>
<td >compile css</td>
</tr>
</thead>
<tbody>

<tr>
<td><b>.width-{n}</b></td>
<td>0</td>
<td>400</td>
<td>2</td>
<td>width: 0px|2px|4px|...|400px</td>
</tr>

<tr><td><b>.width-auto</b></td><td>--</td><td>--</td><td>--</td><td>width: auto</td></tr>
<tr><td><b>.width-100-percent</b></td><td>--</td><td>--</td><td>--</td><td>width: 100%</td></tr>



<tr>
<td><b>.height-{n}</b></td>
<td>0</td>
<td>400</td>
<td>2</td>
<td>height: 0px|2px|4px|...|400px</td>
</tr>

<tr><td><b>height-auto</b></td><td>--</td><td>--</td><td>--</td><td>height: auto</td></tr>
<tr><td><b>height-100-percent</b></td><td>--</td><td>--</td><td>--</td><td>height: 100%</td></tr>


<tr>
<td><b>.square-{n}</b></td>
<td>0</td>
<td>400</td>
<td>2</td>
<td>
width: 0px|2px|4px|...|400px; <br>
height: 0px|2px|4px|...|400px; <br>
</td>
</tr>


<tr>
<td>
<b>.size-{m}-{n}</b> <br>
<b>.rectangle-{m}-{n}</b> <br>
</td>
<td>0</td>
<td>100</td>
<td>2</td>
<td>
width: 0px|2px|4px|...|100px; <br>
height: 0px|2px|4px|...|100px; <br>
</td>
</tr>


<tr>
<td><b>.border-radius-{n}</b></td>
<td>0</td>
<td>100</td>
<td>2</td>
<td>border-radius: 0px 2px 4px 6px 8px 10px 12px 14px 16px 18px 20px 22px 24px 26px 28px 30px 32px 34px 36px 38px 40px 42px 44px 46px 48px 50px 52px 54px 56px 58px 60px 62px 64px 66px 68px 70px 72px 74px 76px 78px 80px 82px 84px 86px 88px 90px 92px 94px 96px 98px 100px;</td>
</tr>

<tr>
<td>
<b>.border-radius-{n}-percent</b>
</td>
<td>0</td>
<td>100</td>
<td>10</td>
<td>border-radius: 0% 10% 20% 30% 40% 50% 60% 70% 80% 90% 100%;</td>
</tr>

<tr>
<td>
<b>.border-1px-{type}</b>
</td>
<td>--</td>
<td>--</td>
<td>--</td>
<td>
border: 1px solid | dashed | dotted | double | groove | hidden | inset | outset | ridge | none | initial | inherit;
<br>
<br>
<i>
*In addition, You need to add custom color to the element, 
such as :<br><b>border-color: red;</b>
</i>
</td>
</tr>

<tr>
<td>
<b>
.background-white <br>
.bg-white
</b>
</td>
<td>--</td>
<td>--</td>
<td>--</td>
<td>background-color: #fff;</td>
</tr>

<tr>
<td>
<b>
.background-black <br>
.bg-black
</b>
</td>
<td>--</td>
<td>--</td>
<td>--</td>
<td>background-color: #000;</td>
</tr>

<tr>
<td>
<b>
.background-black-{n} <br>
.bg-black-{n}
</b>
</td>
<td>0</td>
<td>100</td>
<td>1</td>
<td>background-color: rgba(0, 0, 0, 0.0|0.01|0.02|...|0.99|1);</td>
</tr>

<tr>
<td>
<b>
.color-white-{n}
</b>
</td>
<td>0</td>
<td>100</td>
<td>1</td>
<td>color: rgba(255, 255, 255, 0.0|0.01|0.02|...|0.99|1); <br>
<i>*In addition,color-white = color-white-100,</i>
</td>
</tr>

<tr>
<td>
<b>
.cursor-{name}
</b>
</td>
<td>--</td>
<td>--</td>
<td>--</td>
<td>cursor: default | pointer | move | wait | help | text | crosshair | not-allowed | grab | grabbing | zoom-in | zoom-out | all-scroll | col-resize | row-resize | n-resize | e-resize | s-resize | w-resize | ne-resize | nw-resize | se-resize | sw-resize | ew-resize | ns-resize | nesw-resize | nwse-resize | none | context-menu | cell | vertical-text | alias | copy | progress | no-drop | not-allowed | e-resize | w-resize | ns-resize | ew-resize | nesw-resize | nwse-resize | col-resize | row-resize | n-resize | ne-resize | e-resize | se-resize | s-resize | sw-resize | w-resize | nw-resize | move | grab | grabbing | all-scroll | zoom-in | zoom-out | help;</td>
</tr>

<tr>
<td>
<b>
.display-{name}
</b>
</td>
<td>--</td>
<td>--</td>
<td>--</td>
<td>display: block | inline | inline-block | flex | inline-flex | grid | inline-grid | table | inline-table | contents | list-item | run-in | none;</td>
</tr>

<tr>
<td>
<b>
.vertical-divider <br>
.divider-vertical
</b>
</td>
<td>--</td>
<td>--</td>
<td>--</td>
<td>border-left: 1px solid rgba(5, 5, 5, .06);<br/>height: 100%;</td>
</tr>

<tr>
<td>
<b>
.horizontal-divider <br>
.divider-horizontal
</b>   
</td>
<td>--</td>
<td>--</td>
<td>--</td>
<td>border-top: 1px solid rgba(5, 5, 5, .06);<br/>width: 100%;</td>
</tr>

<tr>
<td>
<b>.font-{n}-regular</b>
</td>
<td>10</td>
<td>50</td>
<td>2</td>
<td>font-size: 10px 12px 14px 16px 18px 20px 22px 24px 26px 28px 30px 32px 34px 36px 38px 40px 42px 44px 46px 48px 50px; <br/>font-family: PingFangSC-Regular, PingFang SC, sans-serif; <br/> font-weight: 400; </td>
</tr>

<tr>
<td>
<b>.font-{n}-medium</b>
</td>
<td>10</td>
<td>50</td>
<td>2</td>
<td>font-size: 10px 12px 14px 16px 18px 20px 22px 24px 26px 28px 30px 32px 34px 36px 38px 40px 42px 44px 46px 48px 50px; <br/>font-family: PingFangSC-Medium, PingFang SC, sans-serif; <br/> font-weight: 500; </td>
</tr>

<tr>
<td>
<b>.font-weight-{n}</b>
</td>
<td>100</td>
<td>1000</td>
<td>100</td>
<td>font-weight: 100 | 200 | 300 | 400 | 500 | 600 | 700 | 800 | 900;</td>
</tr>


<tr>
<td>
<b>.margin-{n}</b>
</td>
<td>0</td>
<td>100</td>
<td>2</td>
<td>margin: 0px 2px 4px 6px 8px 10px 12px 14px 16px 18px 20px 22px 24px 26px 28px 30px 32px 34px 36px 38px 40px 42px 44px 46px 48px 50px 52px 54px 56px 58px 60px 62px 64px 66px 68px 70px 72px 74px 76px 78px 80px 82px 84px 86px 88px 90px 92px 94px 96px 98px 100px;</td>
</tr>

<tr>
<td>
<b>.margin-{m}-{n}</b>
</td>
<td>0</td>
<td>100</td>
<td>2</td>
<td>margin: [0px, 2px, ... 100px] [0px, 2px, ... 100px];</td>
</tr>

<tr>
<td>
<b>.margin-{direction}-{n}</b>
</td>
<td>0</td>
<td>100</td>
<td>2</td>
<td>margin-{ left | right | bottom | top }: 0px 2px 4px 6px 8px 10px 12px 14px 16px 18px 20px 22px 24px 26px 28px 30px 32px 34px 36px 38px 40px 42px 44px 46px 48px 50px 52px 54px 56px 58px 60px 62px 64px 66px 68px 70px 72px 74px 76px 78px 80px 82px 84px 86px 88px 90px 92px 94px 96px 98px 100px;</td>
</tr>


<tr>
<td>
<b>.padding-{n}</b>
</td>
<td>0</td>
<td>100</td>
<td>2</td>
<td>padding: 0px 2px 4px 6px 8px 10px 12px 14px 16px 18px 20px 22px 24px 26px 28px 30px 32px 34px 36px 38px 40px 42px 44px 46px 48px 50px 52px 54px 56px 58px 60px 62px 64px 66px 68px 70px 72px 74px 76px 78px 80px 82px 84px 86px 88px 90px 92px 94px 96px 98px 100px;</td>
</tr>

<tr>
<td>
<b>.padding-{m}-{n}</b>
</td>
<td>0</td>
<td>100</td>
<td>2</td>
<td>padding: [0px, 2px, ... 100px] [0px, 2px, ... 100px];</td>
</tr>

<tr>
<td>
<b>.padding-{direction}-{n}</b>
</td>
<td>0</td>
<td>100</td>
<td>2</td>
<td>padding-{ left | right | bottom | top }: 0px 2px 4px 6px 8px 10px 12px 14px 16px 18px 20px 22px 24px 26px 28px 30px 32px 34px 36px 38px 40px 42px 44px 46px 48px 50px 52px 54px 56px 58px 60px 62px 64px 66px 68px 70px 72px 74px 76px 78px 80px 82px 84px 86px 88px 90px 92px 94px 96px 98px 100px;</td>
</tr>
<tr><td><b>.image-width-fit,<br> .image-height-auto</b></td><td>--</td><td>--</td><td>--</td><td>object-fit: cover; <br> background-size: auto 100%;</td></tr>
<tr><td><b>.image-height-fit,<br> .image-width-auto</b></td><td>--</td><td>--</td><td>--</td><td>object-fit: contain; <br> background-size: 100% auto;</td></tr>

<tr>
<td>
<b><font color="red">*grid layout</font></b>
</td>
<td>--</td>
<td>--</td>
<td>--</td>
<td>
reference: 
<a href="https://ant.design/components/grid">antd design grid</a>
<br />
row, col-{n}, offset-{n}
n from 1 to 24
</td>
</tr>

<tr>
<td>
<b><font color="red">*flex layout</font></b>
</td>
<td>--</td>
<td>--</td>
<td>--</td>
<td>

.flex, .flex.wrap<br>
.flex-column, .flex-column.wrap<br>
child: align-self-end<br>
child: align-self-center<br>
.flex-space-between .flex-justify-content-space-between<br>
.flex-space-around .flex-justify-content-space-around<br>
.flex-center .flex-justify-center .flex-justify-content-center<br>
.flex-align-start <br>
.flex-align-center <br>
.flex-align-end <br>

</td>
</tr>

<tr>
<td>
<b>.gap-{n}</b>
</td>
<td>0</td>
<td>40</td>
<td>2</td>
<td>gap: 0px 2px 4px 6px 8px 10px 12px 14px 16px 18px 20px 22px 24px 26px 28px 30px 32px 34px 36px 38px 40px;</td>
</tr>

<tr>
<td>
<b>.gap-{m}-{n}</b>
</td>
<td>0</td>
<td>40</td>
<td>2</td>
<td>gap: [0px, 2px, ... 40px] [0px, 2px, ... 40px];</td>
</tr>

<tr>
<td>
<b>.opacity-{n}</b>
</td>
<td>0</td>
<td>100</td>
<td>10</td>
<td>opacity: 0% | 10% | 20% | 30% | 40% | 50% | 60% | 70% | 80% | 90% | 100%;</td>
</tr>

<tr>
<td>
<b>.position-{type}</b>
</td>
<td>--</td>
<td>--</td>
<td>--</td>
<td>position: {absolute, relative, fixed, sticky, static, inherit, initial, unset}</td>
</tr>

<tr>
<td>
<b>.float-{direction}</b>
</td>
<td>--</td>
<td>--</td>
<td>--</td>
<td>float: {left, right}</td>
</tr>

<tr>
<td>
<b>.z-index-{n}</b>
</td>
<td>0</td>
<td>10</td>
<td>1</td>
<td>z-index: 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10;</td>
</tr>

<tr>
<td>
<b>.{direction}-{n}</b>
</td>
<td>0</td>
<td>100</td>
<td>2</td>
<td>{top | right | bottom | left}: 0px | 2px | 4px | 6px | 8px | 10px | 12px | 14px | 16px | 18px | 20px | 22px | 24px | 26px | 28px | 30px | 32px | 34px | 36px | 38px | 40px | 42px | 44px | 46px | 48px | 50px | 52px | 54px | 56px | 58px | 60px | 62px | 64px | 66px | 68px | 70px | 72px | 74px | 76px | 78px | 80px | 82px | 84px | 86px | 88px | 90px | 92px | 94px | 96px | 98px | 100px;</td>
</tr>


<tr>
<td>
<b>.overflow-{type}</b>
</td>
<td>--</td>
<td>--</td>
<td>--</td>
<td>overflow: {auto | hidden | scroll | visible}</td>
</tr>

<tr>
<td>
<b>.overflow-{axis}-{type}</b>
</td>
<td>--</td>
<td>--</td>
<td>--</td>
<td>overflow-{x | y} - {auto | hidden | scroll | visible}:{auto | hidden | scroll | visible}</td>
</tr>



<tr>
<td>
<b>.move-towards-{direction}-{n}</b>
</td>
<td>0</td>
<td>100</td>
<td>2</td>
<td>position: relative; <br> { bottom | top | left | right }: -0px | -2px | -4px | -6px | -8px | -10px | -12px | -14px | -16px | -18px | -20px | -22px | -24px | -26px | -28px | -30px | -32px | -34px | -36px | -38px | -40px | -42px | -44px | -46px | -48px | -50px | -52px | -54px | -56px | -58px | -60px | -62px | -64px | -66px | -68px | -70px | -72px | -74px | -76px | -78px | -80px | -82px | -84px | -86px | -88px | -90px | -92px | -94px | -96px | -98px | -100px;</td>
</tr>

<tr>
<td>
<b>.{direction}-{n}-percent</b>
</td>
<td>0</td>
<td>100</td>
<td>10</td>
<td>{top | right | bottom | left}: 0% | 10% | 20% | 30% | 40% | 50% | 60% | 70% | 80% | 90% | 100%;</td>
</tr>

<tr>
<td>
<b>.rotate-{n}-deg</b>
</td>
<td>0</td>
<td>360</td>
<td>1</td>
<td>transform: rotate(0deg) | rotate(1deg) ... | rotate(360deg);</td>
</tr>

<tr>
<td>
<b>.ellipsis-{n}-line</b>
</td>
<td>1</td>
<td>5</td>
<td>1</td>
<td>display: -webkit-box; <br>text-overflow: ellipsis; <br> -webkit-line-clamp: 1 | 2 | 3 | 4 | 5; <br> -webkit-box-orient: vertical; <br> overflow: hidden;</td>
</tr>

<tr>
<td>
<b>.line-height-{n}</b>
</td>
<td>100</td>
<td>300</td>
<td>10</td>
<td>line-height: 100% | 110% | 120% | 130% | 140% | 150% | 160% | 170% | 180% | 190% | 200% | 210% | 220% | 230% | 240% | 250% | 260% | 270% | 280% | 290% | 300%;</td>
</tr>

<tr>
<td>
<b>.word-break-{type}</b>
</td>
<td>--</td>
<td>--</td>
<td>--</td>
<td>word-break-{normal | break-all | keep-all | break-word}</td>
</tr>

<tr>
<td>
<b>.transition-{n}-ms</b>
</td>
<td>50</td>
<td>3000</td>
<td>50</td>
<td>transition: all 50ms | 100ms | 150ms | 200ms | 250ms | 300ms | 350ms | 400ms | 450ms | 500ms | 550ms | 600ms | 650ms | 700ms | 750ms | 800ms | 850ms | 900ms | 950ms | 1000ms | 1050ms | 1100ms | 1150ms | 1200ms | 1250ms | 1300ms | 1350ms | 1400ms | 1450ms | 1500ms | 1550ms | 1600ms | 1650ms | 1700ms | 1750ms | 1800ms | 1850ms | 1900ms | 1950ms | 2000ms | 2050ms | 2100ms | 2150ms | 2200ms | 2250ms | 2300ms | 2350ms | 2400ms | 2450ms | 2500ms | 2550ms | 2600ms | 2650ms | 2700ms | 2750ms | 2800ms | 2850ms | 2900ms | 2950ms | 3000ms;</td>
</tr>

<tr>
<td>
<b>.user-select-none</b>
</td>
<td>--</td>
<td>--</td>
<td>--</td>
<td>user-select: none;</td>
</tr>

<tr>
<td>
<b>.{vw|vh}-{n}</b>
</td>
<td>0</td>
<td>100</td>
<td>1</td>
<td>{width | height}: 0vw | 1vw | 2vw | 3vw | 4vw | 5vw | 6vw | 7vw | 8vw | 9vw | 10vw | 11vw | 12vw | 13vw | 14vw | 15vw | 16vw | 17vw | 18vw | 19vw | 20vw | 21vw | 22vw | 23vw | 24vw | 25vw | 26vw | 27vw | 28vw | 29vw | 30vw | 31vw | 32vw | 33vw | 34vw | 35vw | 36vw | 37vw | 38vw | 39vw | 40vw | 41vw | 42vw | 43vw | 44vw | 45vw | 46vw | 47vw | 48vw | 49vw | 50vw | 51vw | 52vw | 53vw | 54vw | 55vw | 56vw | 57vw | 58vw | 59vw | 60vw | 61vw | 62vw | 63vw | 64vw | 65vw | 66vw | 67vw | 68vw | 69vw | 70vw | 71vw | 72vw | 73vw | 74vw | 75vw | 76vw | 77vw | 78vw | 79vw | 80vw | 81vw | 82vw | 83vw | 84vw | 85vw | 86vw | 87vw | 88vw | 89vw | 90vw | 91vw | 92vw | 93vw | 94vw | 95vw | 96vw | 97vw | 98vw | 99vw | 100vw;</td>
</tr>

</tbody>
</table>


## Author

👤 **caowei**

* Website: https://tsaowe.github.io
* Github: [@tsaowe](https://github.com/tsaowe)

## Show your support

Give a ⭐️ if this project helped you!

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
