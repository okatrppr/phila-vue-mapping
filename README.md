# phila-vue-mapping ([@phila/vue-mapping](https://www.npmjs.com/package/@phila/vue-mapping) in [npmjs.com](https://npmjs.com))

phila-vue-mapping is a library of Vue components that can be used in mapping apps which use [Vue.js](https://vuejs.org/v2/guide/) and [Vuex](https://vuex.vuejs.org/).  It includes many mapping components such as [Maps](https://github.com/CityOfPhiladelphia/phila-vue-mapping/wiki/Map), [ESRI WebMaps](https://github.com/CityOfPhiladelphia/phila-vue-mapping/wiki/EsriWebMap), and [Cyclomedia Widgets](https://github.com/CityOfPhiladelphia/phila-vue-mapping/wiki/CyclomediaWidget), etc.

![](https://s3.amazonaws.com/mapboard-images/phila-vue-mapping/phila-vue-mapping.JPG)

## To Include The Components In Your App
* in a bundled app, use npm:

    `npm install @phila/vue-mapping`

* in an html file, use the CDN:

    `<script src="//unpkg.com/@phila/vue-mapping@2.0.5/dist/phila-vue-mapping.js"></script>`


## Usage
Check out [the wiki](https://github.com/CityOfPhiladelphia/phila-vue-mapping/wiki) for usage documentation.

## Release Notes

### 2.1.1 - 5/5/2020

* fixes problems with pushing to npm

### 2.1.0 - 5/5/2020

* merges changes for use in pinboard and viewerboard

### 2.0.10 - 4/1/2020

* fixes css for rendering map and cyclomedia in property data explorer

### 2.0.9 - 2/6/2020

### 2.0.8 - 2/6/2020

* fixes pictometry popout button

### 2.0.7 - 2/6/2020

* lints files for release

### 2.0.6 - 2/6/2020

* fixes for viewerboard basemap toggle

### 2.0.5 - 1/31/2020

* pushes again after linting project

### 2.0.4 - 1/31/2020

* changes to make new destination work

### 2.0.3 - 1/31/2020

* uses major updates to cyclomedia
* pushes to @phila/vue-mapping instead of @philly/vue-mapping

### 2.0.2 - 12/30/2019

### 2.0.1 - 12/19/2019

### 2.0.0 - 12/17/2019

### 1.0.47 - 10/23/2019

* correctly fixes date-fns

### 1.0.46 - 10/23/2019

* attempt to fix date-fns

### 1.0.45 - 10/23/2019

* you have to use the following with this:

    "@vue/cli-plugin-babel": "^4.0.5",
    "@vue/cli-plugin-eslint": "^4.0.5",
    "@vue/cli-service": "^4.0.5",

### 1.0.44 - 10/22/2019

* updates from dependabot

### 1.0.43 - 10/17/2019

* adds linting, fixes VectorMarker by moving changes from update lifecycle hook to a watch

### 1.0.42 - 10/9/2019

* Uses update to L.esri.Webmap to add datetime to popups

### 1.0.41 - 10/7/2019

* Monthly package upgrades, merges in all changes to work with pvd upgrade

### 1.0.40 - 9/24/2019

* Changes for adapting to Cyclomedia 19.12

### 1.0.39 - 9/23/2019

* Changes for adapting to Cyclomedia 19.12

### 1.0.38 - 9/23/2019

* Changes for adapting to Cyclomedia 19.12

### 1.0.37 - 9/6/2019

* Adds to Polyline.vue to fix style changes

### 1.0.36 - 9/6/2019

* Monthly package upgrades

### 1.0.35 - 8/9/2019

* Adds border to address search

### 1.0.34 - 8/9/2019

* Monthly package upgrades

### 1.0.33 - 7/11/2019

* Upgrades lodash-es and lodash.defaultsdeep

### 1.0.32 - 6/20/2019

* changes for Pinboard

### 1.0.31 - 6/2/2019

* Uses axios 0.19.0 to fix security bug

### 1.0.30 - 5/30/2019

* Adds components/OverlaySelectControl.vue for toggling between two years of data in CleanPhl.
* Changes made over initial development of resource finder.
