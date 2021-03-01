# PIXEL.css

This repo extracted the pixel art code from the fun and famous [NES.css](https://github.com/nostalgic-css/NES.css).

To create your own pixel art, please change the bitmap in `scss/mario.scss` (or rename to your favorite character :P) and run:

```bash
sass --no-source-map scss/mario.scss css/mario.css
```

then include the generated css file to your website.

If you would like to edit little by little, you could try:

```bash
sass --watch --no-source-map scss/mario.scss css/mario.css
```

to make the sass compiler recompile automatically upon changes.

Click [here](https://zhuzilin.github.io/PIXEL.css/) for the running Mario in `index.html`!
