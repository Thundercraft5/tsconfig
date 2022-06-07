# tsconfig
TSConfigs for myself.

**List of configurations:**
* NodeJS
	* `node10` (CommonJS)
	* `node12` (ESM, ES2019)
	* `node14` (ESM, ES2020)
	* `node16` (ESM, ES2021)
	* `node17` (ESM, ES2022)
	* `node18` (ESM, ESNext)
    	* `node18-decl` (ESM, ESNext, emits declarations only to ./dist) 
    	* `node18-build` (ESM, ESNext, emits declarations & js to ./dist) 
* Browser (All AMD)
    * `browser`
    * `browser-es5` (ES5)
    * `browser-es6` (ES6)
	* `browser-esnext` (ESNext)
* `base` (Base configuration for all others)
* `esm` (Base configuration for ESM-based configurations)
* `esm-node` (Same as `esm`, but for NodeJS)