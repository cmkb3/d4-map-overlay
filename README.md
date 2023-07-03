# Diablo IV: Map Overlay

## Example

![Overlay on test_image.png](https://github.com/mxtsdev/d4-map-overlay/assets/58796811/3c05fe1e-c586-42ad-8219-e023de74209e)

## How-to instructions

Open terminal (win10/11), run: winget install Anaconda.Anaconda3
After install open 'Anaconda Powershell Prompt'
Navigate to this program's file directory, e.g.: CD C:\Downloads\d4-map-overlay\

Run commands:
python3 -m pip install -r requirements.txt
python3 .\d4-altar-overlay.py

When ingame, open the map, then press F1 to overlay altar of lilith locations or F2 to overlay mysterious chest locations.
Pressing M, T, or left mouse click will clear the overlay.

Would like to eventually allow scrolling of the overlay along with the D4 map.
