## FT231x based converter to RJ11 connector

![Board top view](https://raw.githubusercontent.com/martonmiklos/robomow_usb_adapter/master/docs/top.png)
![Board bottom view](https://raw.githubusercontent.com/martonmiklos/robomow_usb_adapter/master/docs/bottom.png)

Size: 42.44 x 17.78 mm

Drawn in EAGLE 9.x

Warning pozor!! The TX/RX is swapped in the board in the repo, however I stopped using EAGLE and it is not likely, that I am going to fix it.
At some point I might recreate the design in Kicad.

The board has two variants:

### Robomow interface for RM-5xx series 

Normal UART 5V operation for used with Robomow RM toolkit.

You need to invert the both TX and RX lines with the [FT_Prog](https://ftdichip.com/utilities/#ft_prog).

![Invert TX RX in FT Prog](https://raw.githubusercontent.com/martonmiklos/robomow_usb_adapter/master/docs/FProg_3.gif)


Pinout:
![Robomow RM series RJ10 pinout](https://raw.githubusercontent.com/martonmiklos/robomow_usb_adapter/master/robomow_pinout.png)

### RS-485 adapter for Sorensen/Ametek DLM series power supplies

For communicating Sorensen DLM series power supplies via RS-485

![Sorensen RS-485 pinout](https://raw.githubusercontent.com/martonmiklos/robomow_usb_adapter/master/sorensen.png)
