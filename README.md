# inky_frame4

To use this code, you will need an [InkyFrame 4.0](https://shop.pimoroni.com/products/inky-frame-4?variant=40443825094739https:/)

For additional reference, you can go to [Pimoroni's official site](https://shop.pimoroni.com/products/inky-frame-4?variant=40443825094739https:/). Drop down about halfway on the page to the "Software" section. There you will find a variety of references. This code leverages MicroPython:

* [(Learn) Getting Started with Inky Frame](https://learn.pimoroni.com/article/getting-started-with-inky-frame)
* [(Readme) Installing MicroPython](https://github.com/pimoroni/pimoroni-pico/blob/main/setting-up-micropython.md)
* [(Readme) MicroPython FAQs](https://github.com/pimoroni/pimoroni-pico/blob/main/faqs-micropython.md) (and troubleshooting)
* [Download pirate-brand MicroPython](https://github.com/pimoroni/pimoroni-pico/releases) (you'll want the Inky Frame.uf2)
* [MicroPython examples](https://github.com/pimoroni/pimoroni-pico/tree/main/micropython/examples/inky_frame)
* [PicoGraphics function reference](https://github.com/pimoroni/pimoroni-pico/tree/main/micropython/modules/picographics)


# Getting Started

## IDE: Thonny

More details are provided at [https://learn.pimoroni.com/article/getting-started-with-inky-frame#micropython-and-inky-frame](https://learn.pimoroni.com/article/getting-started-with-inky-frame#micropython-and-inky-frame)

The key here is that you'll need a program called [Thonny](https://thonny.org/https:/) in order to connect to the InkyFrame and deploy code.

Once you have Thonny installed, you can see the code that is on the InkyFrame, deploy new code, and run code for testing and debugging.

## Firmware

Periodically, new firmware will be released for the hardware. Because this is a cluster of hardware (display, microcontroller, etc.), Pimoroni releases [firmware](https://github.com/pimoroni/pimoroni-pico/blob/main/setting-up-micropython.mdhttps:/). The most recent firmware for the InkyFrame 4.0 can be found at [https://github.com/pimoroni/pimoroni-pico/releases](https://github.com/pimoroni/pimoroni-pico/releaseshttps:/). You'll be looking for a file that follows the naming standard *pimoroni-picow_inky_frame-vx.x.x-micropython.uf2*

To load new firmware:

1. Hold the reset button on the back of the InkyFrame
2. Plug the InkyFrame into your computer
3. Release the reset button once plugged in
4. An external storage folder should appear in your file explorer
5. Drag the uf2 file you downloaded into this new external storage folder
6. Once the upload is complete, the InkyFrame will automatically disconnect and the firmware is now updated

## Adding This Code

To put this code on your InkyFrame:

1. Download the code in this repo
2. Install Thonny and start the program
3. Plug your InkyFrame into your computer
4. Find the InkyFrame in the menu at the bottom right of the screen![Screenshot of Thonny](https://cdn.learn.pimoroni.com/article/getting-started-with-inky-frame/assets/thonny2_v2.png?width=800)
5. Once connected, press the stop sign button in the menu bar (this stops the code from running on the InkyFrame). You can only interact with the InkyFrame when there is no code running on it.
6. Now you can copy files and folders from your computer (top left window) to the InkyFrame (bottom left window).
7. When you copy this code, do not copy the root directory (inky_frame4), just the files and folders contained within that folder.
