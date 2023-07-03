# 🐸 Lucas games + Sprig Web Template 👾

> This repository is fully based on https://github.com/jzaleta/sprig-web-template from [Javi](https://github.com/jzaleta), thanks Javi!

## Template Quickstart 

The index.html file has everything you need to get started, just add your js sprig game in the following segment replacing my game:

```html
<!-- The Sprig device's aspect ratio is 5:4  -->
<canvas width="500" height="400" id="canvas" tabindex="0"></canvas>

<script type="module">
  import { webEngine } from "https://esm.sh/sprig@1/web"

  function runGame(api) {
    // Your game code here.
  }

  const game = webEngine(document.getElementById("canvas"))
  runGame(game.api)
</script>
```
Remember, to make a Sprig game you'll need to use [Sprig's Web Editor](https://sprig.hackclub.com/~/new).
