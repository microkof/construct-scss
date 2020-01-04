# construct-scss
A CSS libaray for constructing layout quickly.

## Build

```
sass scss/construct-h5.scss:css/construct-h5.css scss/construct-uniapp.scss:css/construct-uniapp.css scss/construct-wxss.scss:css/construct.wxss -s compressed
```

## import

```
// H5 SCSS
import 'construct-scss/scss/construct-h5.scss';
// H5 CSS
import 'construct-scss/css/construct-h5.css';

// WXSS SCSS
import 'construct-scss/scss/construct-wxss.scss';
// WXSS
import 'construct-scss/css/construct.wxss';

// uni-app SCSS
import 'construct-scss/scss/construct-uniapp.scss';
// uni-app CSS
import 'construct-scss/css/construct-uniapp.css';
```