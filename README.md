# SimJSLoader

[![Dependency Status](https://david-dm.org/muicss/loadjs.svg)]()
[![devDependency Status](https://david-dm.org/muicss/loadjs/dev-status.svg)]()
=========

Miniscript to load dynamic js files from [@GAYTH](https://github.com/gaiththewolf).

## Version
  Last : 1.0.1

## Install

```sh
npm install simjsloader@1.0.1
-
git+https://github.com/GTeCHSOFT/SimJSLoader.git
```

## Example:
```html
<script type='text/javascript' src='../js/jquery.js'></script>
<script type='text/javascript' src='../js/SimJSLoader.js'></script>
```
```js
/**
 * 
 * @param {string} racine // Exemple : /GADM/JS/Plugin/
 * @param {Object[]} file // list of file to load [GADM.JS , test/test.js]
 * @param {boolean} log_success //log success loads JS
 * @param {boolean} log_erro //log Error loads JS
 * @param {requestCallback} _callback //call back after load JS
 */
simJSLoader('../racine/js/',['file_1.js','test/bib2.js',..,'file/dist/ff.min.js'],false,true,function(){
 // todo after load js files
})
```

## License

SimJSLoader.js is [GNU v3.0 Licensed](https://github.com/gaiththewolf/SimJSLoader/blob/master/LICENSE).
