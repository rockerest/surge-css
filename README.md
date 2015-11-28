# Surge CSS
## Simple, Responsive, Grids
----
### Get it

 1. Install with [NPM](https://www.npmjs.com):

 ```
 npm install surge-css
 ```

 2. Download from [Github](https://github.com/rockerest/surge-css):

 ```
 git clone https://github.com/rockerest/surge-css
 ```

### Use it

 1. Make a grid container:

 ```
 <div class="surge-grid">
 </div>
 ```

 2. Put some columns in it:

 ```
 <div class="surge-grid">
    <div class="surge-column-1/4">
        A quarter column
    </div>
 </div>
 ```

 3. Design mobile-first, and add responsive columns:

 ```
 <div class="surge-grid">
    <div class="surge-column-1 surge-column-tablet-1/2 surge-column-desktop-1/4">
        A responsive column
    </div>
 </div>
 ```

### Customize it

 1. Add a vendor variable overrides file to the beginning of your sass build pipeline
 2. Override [some variables](https://github.com/rockerest/surge-css/blob/master/src/scss/_variables.scss)

 ```
 $surge-name: "jim";
 $surge-separator: "|";
 $surge-column-name: "tower";
 $surge-grid-name: "squares";
 ```

 3. `@import` `surge-css/src/scss/surge.scss` into your sass build pipeline
 4. Write your grids like a boss:

 ```
 <div class="jim|squares">
    <div class="jim|tower|1 jim|tower|tablet|1/2 jim|tower|desktop|1/4">
        A responsive column
    </div>
 </div>
 ```

### Find more info about it

[The *real* documentation](surge-css.com)

### Report a problem with it

Submit an issue at the [Github issue tracker](https://github.com/rockerest/surge-css/issues)
