

# Okiba / SizesCache
A class to compute and cache element sizes.




```javascript
import { qs } from '@okiba/dom'
import SizesCache from '@okiba/size-cache'

const sizes = SizesCache.get(qs('#app'))
console.log(sizes)
```



### Installation

```bash
npm i --save @okiba/sizes-cache
```

Or import it directly in the browser
```html
<script type="module" src="https://unpkg.com/@okiba/sizes-cache/index.js"></script>
```

## Usage

```javascript
import SizesCache from '@okiba/sizes-cache'
```

#### Untranspiled code 🛑
Okiba UI packages are not transpiled, so __don't forget to transpile them with your favourite bundler__.
For example, using Babel with Webpack, you should prevent imports from okiba to be excluded from transpilation, like follows:
```javascript
{
  test: /\.js$/,
  exclude: /node_modules\/(?!(@okiba)\/).*/,
  use: {
    loader: 'babel-loader',
    options: {
      presets: ['@babel/preset-env']
    }
  }
}
```







## get(el)


Element's sizes getter







#### Arguments


##### + `el`: `Element`







## compute(el)


Computes element's sizes







#### Arguments


##### + `el`: `Element`







## onResize()


Updates elements' sizes on resize







## listen()


Adds resize event listener to EventManager







## unlisten()


Removes resize event listener from EventManager







## reset()


Resets component's data






