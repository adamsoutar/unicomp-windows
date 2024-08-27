# British macOS Unicomp Space-Saver layout for Windows

I have possibly faced a near-unique challenge. But just in-case it isn't and somebody else out there is as mental as I am, here, I saved you the trouble.

This repo contains a mapping for the Unicomp Space Saver M (for macOS) British Layout board for use with Windows 11.

The British macOS layout is not the same as the standard US one, for example it has a `£` symbol on Shift+3. This map also contains the edge-cases such as AltGr+3 for `#`, and correctly mapped `§±~` keys. 

This is essential if you:

 - Program with your Model M keyboard
 - Are British
 - Mostly use a Mac but
 - Sometimes have to use Windows
 - Don't want to swap boards when swapping machines

If all of the above has happened to you, you're welcome!

## Usage

Thanks to Microsoft, setting this up couldn't be easier.

First, download the [Release](https://github.com/adamsoutar/unicomp-windows/releases) and run `setup.exe`.

(No, I don't know why keyboard layouts are in executables either. Or why they're dependent on CPU architecture.)

Open `Settings -> Time & Language`, then press the tiny `...` button on `English (United Kingdom)`, then `Language Options` (naturally where you would expect to find Keyboard Layouts).

Now press `Add a keyboard`, select `United Kingdom - Unicomp Model M Mac`, and remove your old keyboard layout.

If the Unicomp option isn't there, restart the Settings app until it appears.

## Mac text cursor

I recommend using this layout in combination with the following [PowerToys](https://github.com/microsoft/PowerToys) key remap:

<img src="./powertoys.png" width="350">

which gives you Cmd+Left/Right and Cmd+Up/Down for moving the cursor while programming.

## Further editing

If you want to remap things further, open the `klc` file from this repo in [Microsoft Keyboard Layout Creator](https://www.microsoft.com/en-us/download/details.aspx?id=102134).

---

##### Adam Soutar

###### Not licensed, don't care