# SVG #1

[Live Demo](https://codepen.io/FrustrateCoder/pen/zYKyedp)

```css
<style>
.container {
  position: relative;
}

.mysvg1 {
  position: absolute;
}

.mysvg1 path {
  stroke-dasharray: 270;
  stroke-dashoffset: -270;
  animation: trymeRevserse 5s linear infinite ;
  stroke: #1291a8;
}

@keyframes trymeRevserse {
  to {
    stroke-dasharray: 270;
    stroke-dashoffset: 270;
  }
}
</style>
```
```html
<div class="container">
<svg class="mysvg1" xmlns="http://www.w3.org/2000/svg" width="189" height="57" viewBox="0 0 189 57">
    <g fill="none" fill-rule="evenodd" stroke-dasharray="6 8">
        <g stroke="#131F2B" stroke-width="2">
            <g>
                <path d="M-43.202 23.307c20.956-2.707 28.824 16.54 32.644 20.56C42.74 99.947 56.068 7.664 94.564 8c51.614.452 38.985 66.466 80.263 66.466 38.805 0 23.28-50.546 77.108-55" transform="translate(-904 -96) rotate(-90 514 -279) matrix(0 -1 -1 0 145.6 255.798)"/>
            </g>
        </g>
    </g>
</svg>
<div class="half">
<svg class="mysvg2" xmlns="http://www.w3.org/2000/svg" width="189" height="57" viewBox="0 0 189 57">
    <g fill="none" fill-rule="evenodd" stroke-dasharray="6 8">
        <g stroke="#131F2B" stroke-width="2">
            <g>
                <path d="M-43.202 23.307c20.956-2.707 28.824 16.54 32.644 20.56C42.74 99.947 56.068 7.664 94.564 8c51.614.452 38.985 66.466 80.263 66.466 38.805 0 23.28-50.546 77.108-55" transform="translate(-904 -96) rotate(-90 514 -279) matrix(0 -1 -1 0 145.6 255.798)"/>
            </g>
        </g>
    </g>
</svg>
</div>
</div>
```

# SVG #2
[Live Demo](https://codepen.io/FrustrateCoder/pen/BaLvMmy)

```css
.container {
  position: relative;
}

.mysvg1 {
  position: absolute;
}

.mysvg1 path {
  stroke-dasharray: 100;
  animation: trymeRevserse 10s linear infinite ;
  stroke: #1291a8;
}

@keyframes trymeRevserse {
  to {
    stroke-dashoffset: 1000;
  }
}
```

```html
<div class="container">
<svg class="mysvg1" xmlns="http://www.w3.org/2000/svg" width="189" height="57" viewBox="0 0 189 57">
    <g fill="none" fill-rule="evenodd" stroke-dasharray="6 8">
        <g stroke="#131F2B" stroke-width="2">
            <g>
                <path d="M-43.202 23.307c20.956-2.707 28.824 16.54 32.644 20.56C42.74 99.947 56.068 7.664 94.564 8c51.614.452 38.985 66.466 80.263 66.466 38.805 0 23.28-50.546 77.108-55" transform="translate(-904 -96) rotate(-90 514 -279) matrix(0 -1 -1 0 145.6 255.798)"/>
            </g>
        </g>
    </g>
</svg>
<div class="half">
<svg class="mysvg2" xmlns="http://www.w3.org/2000/svg" width="189" height="57" viewBox="0 0 189 57">
    <g fill="none" fill-rule="evenodd" stroke-dasharray="6 8">
        <g stroke="#131F2B" stroke-width="2">
            <g>
                <path d="M-43.202 23.307c20.956-2.707 28.824 16.54 32.644 20.56C42.74 99.947 56.068 7.664 94.564 8c51.614.452 38.985 66.466 80.263 66.466 38.805 0 23.28-50.546 77.108-55" transform="translate(-904 -96) rotate(-90 514 -279) matrix(0 -1 -1 0 145.6 255.798)"/>
            </g>
        </g>
    </g>
</svg>
</div>
</div>
```
