# construct-scss
A CSS libaray for constructing layout quickly.

## Build

```
sass scss/construct-h5.scss:css/construct-h5.css scss/construct-mp.scss:css/construct.wcss -s compressed
```

## import

```js
// H5 版 SCSS
import 'construct-scss/scss/construct-h5.scss';
// H5 版 CSS
import 'construct-scss/css/construct-h5.css';

// 小程序版 SCSS
import 'construct-scss/scss/construct-mp.scss';
// 小程序版 WXSS
@import 'construct-scss/css/construct.wxss';
```