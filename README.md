# United States keyboard with easy access to (German) Umlauts

## Introduction
As a person who moved to Germany, sometimes I have to use Umlauts, but I hate the German Keyboard, especially the chaotic layout of all symbols (except letters).

So, I'm using a US keyboard layout, but with added German Umlauts via AltGr key \
(yes, I have a US keyboard. If you have a German keyboard, [take a look at this twin project](https://github.com/astappiev/win-de-fix-shortcuts)).

The keyboard is a copy of the great work by [@thomasfaingnaert](https://github.com/thomasfaingnaert), his [United States (International) with AltGr dead keys](https://github.com/thomasfaingnaert/win-us-intl-altgr) keyboard, which I used before, but it always confused me to type `ú` instead of `ü` or `ó` instead of `ö`. 

So, I ended up with this mix. Basically, all umlauts are now located on their corresponding letters. E.g. to type `ö`, you just need to press `Alt Gr + o` and to type `Ö` correspondingly just `Alt Gr + Shift + Ö`.

## Layout
Without pressing `AltGr`, the keyboard has a US layout.

When you press `AltGr` or `Shift+AltGr` key, the keys are mapped as following:
![altgr](https://github.com/astappiev/win-us-easy-umlauts/assets/4512729/d2f3c636-d00a-456e-8ce6-44fd82b6d378)
![altgr+shift](https://github.com/astappiev/win-us-easy-umlauts/assets/4512729/6d5a6a7c-7e8c-47cc-9410-6452ba2f8720)

## How to Build or Install
You can download the latest installer from the [releases tab of this repo](https://github.com/astappiev/win-us-easy-umlauts/releases).

If you prefer to build from source, you can open the .KLC source file in Microsoft Keyboard Layout Creator.
You can use [this great guide](https://msklc-guide.github.io/) on how to work in this program.
After opening the file, choose Project > Build DLL and Setup Package in the menu to create an installer.
