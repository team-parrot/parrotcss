# Settings: Colors

Question| Answer
--------|--------
What?   | Quickly set your **text colors** and **background colors**
Why?    | To give you flexibility of using colors consistently and in a smart way

## Defaults
The colors are defined in a list called `$color-palette`. You can find them in `/src/scss/settings/_colors.scss`. These are the default values:

color name | hex value | color
-----------|-----------|--------------
primary    | #db2828   | ![primary](https://dummyimage.com/80x24/db2828.png&text=+)
secondary  | #cacaca   | ![secondary](https://dummyimage.com/80x24/cacaca.png&text=+)
white      | #fefefe   | ![white](https://dummyimage.com/80x24/fefefe.png&text=+)
black      | #0a0a0a   | ![black](https://dummyimage.com/80x24/0a0a0a.png&text=+)
gray       | #767676   | ![gray](https://dummyimage.com/80x24/767676.png&text=+)
red        | #db2828   | ![red](https://dummyimage.com/80x24/db2828.png&text=+)
orange     | #f2711c   | ![orange](https://dummyimage.com/80x24/f2711c.png&text=+)
yellow     | #fbbd08   | ![yellow](https://dummyimage.com/80x24/fbbd08.png&text=+)
olive      | #b5cc18   | ![olive](https://dummyimage.com/80x24/b5cc18.png&text=+)
green      | #21ba45   | ![green](https://dummyimage.com/80x24/21ba45.png&text=+)
teal       | #00b5ad   | ![teal](https://dummyimage.com/80x24/00b5ad.png&text=+)
blue       | #2185d0   | ![blue](https://dummyimage.com/80x24/2185d0.png&text=+)
violet     | #6435c9   | ![violet](https://dummyimage.com/80x24/6435c9.png&text=+)
purple     | #a333c8   | ![purple](https://dummyimage.com/80x24/a333c8.png&text=+)
pink       | #e03997   | ![pink](https://dummyimage.com/80x24/e03997.png&text=+)
brown      | #a5673f   | ![brown](https://dummyimage.com/80x24/A5673F.png&text=+)

## Usage
You can get the value of a color by using the built-in `map-get()` function.

```scss
background-color: map-get($color-palette, primary);
```
