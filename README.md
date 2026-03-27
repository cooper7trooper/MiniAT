![Lain Turn](./Serial_Experiments_Lain/LainTurn.gif)

Licensed under CC BY-NC 4.0
# MiniAT Animations Repository

A collection and guide for MiniAT animation .bin files.
These files contain precompiled animations designed for use with MiniAT-compatible devices.

## Structure
Each theme is broken up into their respective folders. You can then dowload the .BIN file you want and upload it to the miniat.local website.

## Ordering Animations
Each BIN file is in the format XX_BinName.bin. The XX indicates the number in the sequence it sits eg. 01_, 02_, 03_ and 04_. 
For now you can only upload individual files and delete individuals aswell. 
This is a feature that will be improved upon in future.

## MiniAT Storage
The onboard chip can store roughly 1MB of data.
Please keep this in mind when uploading as there is not a detection system in place yet.
Each BIN is very small so it shouldn't be a problem.

# Custom Animations

This will outline the steps to making your own custom MiniAT animation.

## Specifications
The display is Monochrome and has a resolution of 128x128 pixels. 
The delay of each frame is 150ms.

## Workflow
* Firstly I find an image or animation I'd like to animate I then reduce the resolution and colour to match the display
(In the tools section I provide different websites I use to achieve this).
* I then Begin animating the frames inside a program called Graphicsgale.
* Once animated I export the individual .PNG's and import them into [image2cpp](https://javl.github.io/image2cpp/)
(This will combine the frames together for the MiniAT).
* Once you've generated the BIN you can hit download and import it into your MiniAT.

## Tools
* [image2cpp](https://javl.github.io/image2cpp/) For Generating BIN files.
* [GraphicsGale](https://graphicsgale.com/us/) To create the animations.
* [EzGIF](https://ezgif.com/split) To format templates and frames.
* [Wplace Colour Converter](https://pepoafonso.github.io/color_converter_wplace/index.html) To change colours either to monochrome or an easy to shade colour scheme.

## Collaboration
If you’d like to contribute animations to MiniAT, feel free to reach out to me on Etsy. I'd love to add more to this collection!

If you have any questions or ideas contact me on etsy. Enjoy!
