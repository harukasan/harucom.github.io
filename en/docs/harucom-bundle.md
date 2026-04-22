---
layout: doc
title: Harucom Bundle with acrylic panels
permalink: /en/docs/harucom-bundle/
lang: en
ref: docs-harucom-bundle
---

Harucom Bundle with acrylic panels is a kit that combines the Harucom Board with acrylic panels and the screws and spacers to mount them. Just screw it together and you are ready to go.

![Harucom Bundle](/assets/harucom_bundle_picture.jpg)

## What's in the Box

When you open the box, make sure that all of the following items are included.

| Part | Quantity |
|------|----------|
| Harucom Board | 1 |
| Acrylic panel (top) | 1 |
| Acrylic panel (bottom) | 1 |
| M2.5 screw | 8 |
| M2.5 spacer (8mm) | 4 |
| M2.5 threaded spacer (5mm) | 4 |

![Box contents](/assets/harucom_bundle.jpg)

## Assembly

1. Attach the spacers and threaded spacers to the Harucom Board.

   > Do not overtighten the screws. Overtightening can crack the board or the acrylic panels.
   {: .tip}

2. Peel off the protective film from the acrylic panels.

   > If the film is hard to peel off, stick a piece of regular tape or masking tape onto the film and pull — it will come off cleanly.
   {: .tip}

3. Attach the bottom acrylic panel with screws from the underside of the board.

4. Attach the top acrylic panel with screws from the top side of the board. Make sure the buttons fit correctly through the holes.

## Power Switch and Grove Connectors (Optional)

The Harucom Board has footprints for an optional power switch and Grove connectors. You can buy these parts separately and solder them on to enable these features.

The parts are available at Akizuki Denshi:

* [Power switch (slide switch)](https://akizukidenshi.com/catalog/g/g115703/)
* [Grove connector](https://akizukidenshi.com/catalog/g/g112634/)

## Usage

Once assembly is complete, follow the [Getting Started](../getting-started/) guide to boot up your Harucom.

## Updating the Firmware

You can update the Harucom firmware by mounting the board as a USB mass storage device and copying `harucom_os.uf2` onto it.

1. Hold down the BOOTSEL button on the Harucom Board while you plug the USB-C cable into your computer. If the board is already connected, you can instead hold BOOTSEL and press the RESET button.

2. The board will appear on your computer as a USB storage device named `RP2350`.

3. Download `harucom_os.uf2` from the [GitHub releases page](https://github.com/harukasan/harucom-os/releases) and copy it to that USB storage device.

4. Once the file is written, Harucom will automatically restart and boot into the new firmware.

> Make sure to use `harucom_os.uf2`. Writing a different uf2 file may prevent the board from booting correctly.
{: .tip}
