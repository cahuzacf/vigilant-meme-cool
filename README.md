<p align="center">
    <img src="https://user-images.githubusercontent.com/6702424/80216211-00ef5280-863e-11ea-81de-59f3a3d4b8e4.png">  
</p>
<p align="center">
    <i>wesh</i>
    <br>
    <br>
    <img src="https://github.com/garronej/vigilant-meme-cool/workflows/ci/badge.svg?branch=develop">
    <img src="https://img.shields.io/bundlephobia/minzip/vigilant-meme-cool">
    <img src="https://img.shields.io/npm/dw/vigilant-meme-cool">
    <img src="https://img.shields.io/npm/l/vigilant-meme-cool">
</p>
<p align="center">
  <a href="https://github.com/cahuzacf/vigilant-meme-cool">Home</a>
  -
  <a href="https://github.com/cahuzacf/vigilant-meme-cool">Documentation</a>
</p>

# Install / Import

```bash
$ npm install --save vigilant-meme-cool
```

```typescript
import { myFunction, myObject } from "vigilant-meme-cool";
```

Specific imports:

```typescript
import { myFunction } from "vigilant-meme-cool/myFunction";
import { myObject } from "vigilant-meme-cool/myObject";
```

## Import from HTML, with CDN

Import it via a bundle that creates a global ( wider browser support ):

```html
<script src="//unpkg.com/vigilant-meme-cool/bundle.min.js"></script>
<script>
    const { myFunction, myObject } = vigilant_meme_cool;
</script>
```

Or import it as an ES module:

```html
<script type="module">
    import {
        myFunction,
        myObject,
    } from "//unpkg.com/vigilant-meme-cool/zz_esm/index.js";
</script>
```

_You can specify the version you wish to import:_ [unpkg.com](https://unpkg.com)

## Contribute

```bash
npm install
npm run build
npm test
```
