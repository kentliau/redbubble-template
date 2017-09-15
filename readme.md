# Redbubble Template

A Better Redbubble Template.

The dimensions below are suggested by Redbubble, most if not all, are 100% coverage to the products without any scaling up or down.

In other words, all the artwork will auto fit to the product without you changing the scaling and moving it.

If your artwork is double the size of the size specified below, then you should set the scaling to 50% at the "Add New Work" page in Redbubble.

| *                                                      | *                                                      | *                                           |
| :----------------------------------------------------: | :----------------------------------------------------: | :-----------------------------------------: |
| **Standard Print Clothing** <br> `2400 * 3200`         | **Large Print Clothing** <br> `2875 * 3900`            | **Contrast Tanks** <br> `3870 * 4280`       |
| **Women's Chiffon Tops** <br> `3711 * 3814`            | **Graphic T-Shirt Dress** <br> `4020 * 6090`           | **Graphic T-Shirts** <br> `3873 * 4814`     |
| **A-Line Dress** <br> `6310 * 6230`                    | **Stickers** <br> `2800 * 2800`                        | **Phone Cases & Skins** <br> `1187 * 1852`  |
| **Phone Wallets** <br> `2087 * 1956`                   | **Pillows & Totes** <br> `3225 * 3225`                 | **Floor Pillows** <br> `4625 * 4625`        |
| **Prints, Cards & Posters** <br> `5000 * 7100`         | **Pouches, Laptop Skins & Sleeves** <br> `4600 * 3000` | **Duvets** <br> `7632 * 6480`               |
| **Mugs** <br> `2700 * 1624`                            | **Travel Mugs** <br> `2376 * 2024`                     | **Leggings** <br> `4350 * 4032`             |
| **Mini Skirts** <br> `2152 * 2502`                     | **Scarves** <br> `5748 * 5748`                         | **Tablet Cases & Skins** <br> `2696 * 3305` |
| **Drawstring Bags** <br> `2475 * 2775`                 | **Spiral Notebooks** <br> `1756 * 2481`                | **Hardcover Journals** <br> `3502 * 2385`   |
| **Clock** <br> `2940 * 2940`                           | **Art Board (Gallery Board)** <br> `4260 * 4260`       | **Acrylic Block** <br> `1860 * 1860`        |
| **Wall Tapestry** <br> `7632 * 6480`                   |                                                        |                                             |

Largest artwork required are `7632 * 6480` (~50 megapixels), which are Duvets & Wall Tapestry.
Therefore, a `8000 * 8000` (64 megapixels) creation is sufficient to cover all the products.

If you design in a vector software using `1000 * 1000`, when export to `PNG`, upscale 8 times. For `2000 * 2000` you upscale it 4 times.

## Template Download

![Imgur Image](http://i.imgur.com/0XQNSyA.png)

Clone the repository

## How to use

Two ways of using the template
1. You open the template image in your favorite software and using it as a canvas, size and proportion guide.
2. You already have a artwork in arbitrary size (like from your camera), you then layer the template image on top of your artwork as a canvas, size and proportion guide. You then scale, crop or patch your artwork accordingly.

What the colors mean
- **Green**: Main printing zone, you should focus your design around here.
- **Red**: Bleeding printing zone, your artwork should cover up to this zone, but it should be non crucial as it will be cut off cause by different in size of the same products or small printing offset.
- **Blue**: Rectangular boundary, your artwork should cover up to this point as well, similar to bleeding zone, this zone serve two purpose, one is to give a rectangular constrainst/proportion, second is to compensate the offset cause by printer.

For template without printing zone or bleeding zone specified, it means it is rectangular printing zone, you should avoid design around the edge.

For products like Phone cases/wallet (iPhone and Samsung Galaxy) and iPad cases, avoid design around the cut out for camera, speaker, port, button.

## Special Notes

- **Stickers**
  - Orientation doesn't matter
  - Adaptive ratio
  - Always fit into printable zone
  - `600 * 800` pixels for small
  - `1100 * 1100` pixels for medium
  - `1700 * 1700` pixels for large
  - `2800 * 2800` pixels for x-large
- **Prints, Cards & Posters**
  - Adaptive ratio for poster
  - Other products will fit into printable zone
  - `5000 * 7100` pixels for largest poster
- **Art Board (Gallery Board)**
  - Semi-Adaptive, Predefined Ratio (1, 1.25, 1.4, 1.5)
  - `4260` pixels is the largest size for one side, if you need a square output then use another `4260` pixels for the other side, else use a smaller value for different predefined ratio.
  - Swap width and height to switch between portrait and landscape

## Author Information
- Twitter <[@kentliau](https://twitter.com/kentliau)>
- Redbubble <[kentliau.redbubble.com](https://kentliau.redbubble.com)>
- Donation
  - [![Donate](https://img.shields.io/badge/Donate%202⁶¢-Paypal-blue.svg)](https://www.paypal.me/kentliau/0.64) [![Donate](https://img.shields.io/badge/Donate%202⁷¢-Paypal-blue.svg)](https://www.paypal.me/kentliau/1.28) [![Donate](https://img.shields.io/badge/Donate%202⁸¢-Paypal-blue.svg)](https://www.paypal.me/kentliau/2.56) [![Donate](https://img.shields.io/badge/Donate%202⁹¢-Paypal-blue.svg)](https://www.paypal.me/kentliau/5.12)

## LICENSE

[Creative Commons Attribution 4.0](https://github.com/kentliau/redbubble-template/blob/gh-pages/LICENSE.md)
