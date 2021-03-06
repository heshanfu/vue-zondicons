# vue-zondicons
## Easily add Zondicon icons to your vue web project

**Installation**
```
npm install --save vue-zondicons
```

**To Use**

Browse Zondicons on the [Zondicon website](http://www.zondicons.com/icons.html)

To add an icon convert the icon name listed on the Zondicon website from hypen case to Pascalcase

ie. To use the Zondicon `arrow-left` you would convert it to `ArrowLeft`

```javascript
  <Zondicon icon="ArrowLeft" />
```

You can also pass css classes to the Zondicon `svg` element

Note: `fill-content` and `text-red` are from the Tailwinds CSS library and `vue-zondicons` doesnt come with any css.
```javascript
  import Zondicon from 'vue-zondicons'

  <Zondicon icon="ArrowLeft" class="fill-current text-red"/>
```

**Note**

The icon `filter` has been changed to `FilterIcon` since `filter` is a registered keyword in Vuejs and will throw errors.


## Project setup
```bash
npm install
```

## Development setup

clone this repo 
```bash
npm install # Install dependancies

./scripts/make-icons.sh # download zondicons from zondicon repo and generate vue components

npm build # Build package for npm

npm publish 

```

## Pull Request

Pull Requests are always welcome :)

License: MIT

