# PoGO-Awesome
PoGO-Awesome is similar to Font-Awesome. With this CSS library you can easily show Pokémons or Pokémons shadows.

# License
You can use this library for non-comercial projects. Because the images in this library are licensed under a trademark. You can find the following information about copyright en term of use here below:
- [Legal information](http://www.pokemon.com/us/legal/)
- [Terms of use](http://www.pokemon.com/us/terms-of-use/)

# How-to use
## Default
`.pogo` is required to make use of PoGO-Awesome.

**Example:**
```
<div class="pogo pokemon-1"></div>
```

## List of all Pokémons
`.pokemon-*` replace `*` with the number of the pokémon. **Notice:** At this moment the library shown here only contains GEN-1 Pokémons (from #1 up to #151), which is equal to the Pokémon Go game.

**Example:**
```
<div class="pogo pokemon-1"></div>
<div class="pogo pokemon-2"></div>
<div class="pogo pokemon-3"></div>
<div class="pogo pokemon-4"></div>
...
```

## Sizes
PoGO-Awesome has predefined sizes for displaying Pokémon.

**List of available sizes:**
- `.pogo-xs`, 16x16px
- `.pogo-s`, 32x32px
- `.pogo-m`, 64x64px (default size)
- `.pogo-l`, 128x128px
- `.pogo-xl`, 256x256px
- `.pogo-xxl`, 512x512px

**Example:**
- `<div class="pogo pokemon-103 pogo-xs"></div>`
- `<div class="pogo pokemon-103 pogo-xxl"></div>`


## Shadow/Mask (only webkit browsers)
Add the class `.mask` or `.shadow` to the element to get the shadow of the pokemon.

**Example:**
- `<div class="pogo pokemon-123 mask"></div>`
- `<div class="pogo pokemon-145 shadow"></div>`

## Examples
```
<div class="pogo pokemon-53 pogo-l mask"></div> // Pokémon #53 (Persian), bigger than normal size, mask/shadow
<div class="pogo pokemon-33 pogo-s"></div> // Pokémon #33 (Nidorino), smaller than normal size, shown normally
<div class="pogo pokemon-67"></div> // Pokémon #67 (Machoke), normal size, shown normally
```