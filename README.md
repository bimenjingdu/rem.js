# rem.js

[![License MIT](https://img.shields.io/npm/l/rem.js.svg)](https://github.com/zhuweiyou/rem.js/blob/master/LICENSE)
[![NPM Version](https://img.shields.io/npm/v/rem.js.svg)](https://www.npmjs.com/package/rem.js)
[![NPM Download](https://img.shields.io/npm/dt/rem.js.svg)](https://www.npmjs.com/package/rem.js)

移动端页面自动适配脚本，改造自 https://github.com/amfe/lib-flexible

建议直接在 `<head>` 中引入，或者 inline
```html
<script src="rem.js" data-psd="750"></script>
```

默认以设计稿 750px 为基础，1rem = 100px

比如设计稿中 150px，在 css 中就写 1.5rem

也可以自定义 data-psd 为你的设计稿宽度
