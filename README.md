# United States keyboard with easy access to (German) Umlauts

## Introduction
As a person who moved to Germany, sometimes I have to use Umlauts, but I hate German Keyboard, especially the chaotic layour of all symbols (except letters).

So, I'm using US keyboard layour, but with added German Umlauts via AltGr key (yes, I have US keybaord, if you have German keyboard, [take a look at this twin project](https://github.com/astappiev/win-de-fix-shortcuts)).

The keyboard is a copy of great work of @thomasfaingnaert, his [United States (International) with AltGr dead keys]
(https://github.com/thomasfaingnaert/win-us-intl-altgr) keybaord, which I used before, but it always confused me to type `ú` instead of `ü` or `ó` instead of `ö`. 

So I ended up with this mix, basically, all umlauts are now located on their corresponding letters. E.g. to type `ö` you just need to press `Alt Gr + o` and to type `Ö` correspondigly just `Alt Gr + Shift + Ö`.

## Layout
Without pressed `AltGr` the keyboard has US-layout.

When you press `AltGr` or `Shift+AltGr` key, the keys are mapped as following:
![altgr](https://github.com/astappiev/win-us-easy-umlauts/assets/4512729/d2f3c636-d00a-456e-8ce6-44fd82b6d378)
![altgr+shift](https://github.com/astappiev/win-us-easy-umlauts/assets/4512729/6d5a6a7c-7e8c-47cc-9410-6452ba2f8720)

## How to Build or Install
You can download the latest installer from the releases tab of this repo (https://github.com/astappiev/win-us-easy-umlauts/releases).

If you prefer to build from source, you can open the .KLC source file in Microsoft Keyboard Layout Creator.
You can use [this gread guide](https://msklc-guide.github.io/) on how to work in this programm.
After opening the file, choose Project > Build DLL and Setup Package in the menu to create an installer.
