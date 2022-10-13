# Pynvaders
Just a Python Space Invaders emulator, but you can select some options (mono colored, inverted colors, with some colors, with more colors, with background image, etc) before the game starts. 

INSTRUCTIONS:

Put a ROM named 'Invaders.rom' (single file ROM) in the same directory as Py8080.py. Also put all the included files (all sounds and background image) in the same directory.

CONTROLS:

Enter = Insert Coin

Up key = start game

Left and Right Keys = move left and right

Space = Shoot

IMAGES:

![](https://github.com/Zafarion/Pynvaders/blob/53cc0942e0f83948283f7de4293eac1553ba94ad/pics/Pyvaders1.png)
![](https://github.com/Zafarion/Pynvaders/blob/53cc0942e0f83948283f7de4293eac1553ba94ad/pics/Pyvaders2.png)
![](https://github.com/Zafarion/Pynvaders/blob/53cc0942e0f83948283f7de4293eac1553ba94ad/pics/Pyvaders3.png)
![](https://github.com/Zafarion/Pynvaders/blob/53cc0942e0f83948283f7de4293eac1553ba94ad/pics/Pyvaders4.png)
![](https://github.com/Zafarion/Pynvaders/blob/53cc0942e0f83948283f7de4293eac1553ba94ad/pics/Pyvaders5.png)
![](https://github.com/Zafarion/Pynvaders/blob/53cc0942e0f83948283f7de4293eac1553ba94ad/pics/Pyvaders6.png)
![](https://github.com/Zafarion/Pynvaders/blob/b40945d2a334e4a5596a4c1bd62e3b2ea73848aa/pics/Pyvaders7.png)
![](https://github.com/Zafarion/Pynvaders/blob/53cc0942e0f83948283f7de4293eac1553ba94ad/pics/Pyvaders8.png)

UPDATE (12/10/2022):
- Included missing sound (lifegained.wav) and implemented code to play this sound. You need to download the new file and put in the same directory as the other sound files.
- The original arcade has switches that lets the owner set the number of lives, display coin information, score total to gain a new life/ship, etc. Now these switches can be changed on the emulator directly in the IN_PORT2 variable by just setting the starting bits. The values are explained in the beggining of the source code.
- Minor changes in the keyboard listening routine and input/output ports handling.
