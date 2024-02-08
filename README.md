
# Obbax's Pixel Art Helper
## Description
This is the documentation on how to use Obbax's Pixel Art Helper. This mod allows the user to pre-process an image, and then see an outline for constructing it as pixel art in Terraria. The mod is client side, so their is no need for it to be installed by all players on servers.

## How To Use It
Video Tutorial: https://youtu.be/DRQLFm2br94
Utilizing the mod requires two main steps, starting with the pre-processing of the image(s).

### Pre-processing

 1. Download the zip file from this repositiory and extract it.
 2. Before running the .exe file, open "exceptions.txt". This file contains the ids for walls and tiles which you may not want to use (Either because they are tedious to get or just straight up impossible). About halfway through the file should be the word "walls", which denotes the beginning of the section containing wall ids. The ids can be found here: [tiles](https://terraria.wiki.gg/wiki/Tile_IDs) and [walls](https://terraria.wiki.gg/wiki/Wall_IDs)
 <img src="https://lh3.googleusercontent.com/pw/ABLVV85cLBbHzVmxA1N2OvUWozr6RV9pvab5D3WJ3gs4CrYu81uXqsDjnOn-nUDSYd-NOD7Vc5FUAESC4aELi0X64GnfuUcq0wdv3hI-1IEz4M14D_ebTtrB4zKjOVibdIeBqNMK8WdhUOk03MLdwkia5y18=w757-h727-s-no-gm?authuser=0" width="400" height="400"/>
    * This process may be tedious, and can be skipped if you trust my judgement :)
 3. After setting up the exceptions, save the file and run the exe. A window should pop up, which asks for a few things. 
    * The "Alpha Cutoff" is the alpha value at which the script should
    ignore the pixel (from 0 to 255, recommended is 10).
    <img src="https://lh3.googleusercontent.com/pw/ABLVV842lreLHo0MW7u8ru78Tu9cI8WmqWxX0pxm5QoUmoFJ3WN8mRhW5zadqNL6LczLjiFJk6ubh268dalr2trpb8CcXRaRTCgCDk9timGlEWfHzJc1Cd5uWWaCepSFD4zfls2whW_FOylLcNjAcqdPzrQm=w445-h60-s-no-gm?authuser=0"/>
    * The "Name To Save As" is self-explanatory. The name which you want to save the file as. (It will be saved as a .txt file in the same directory as the exe, so don't name it exceptions, or else...)
    <img src="https://lh3.googleusercontent.com/pw/ABLVV85Gj3SEuYQGvXhwCIF_tKCStvHwOid1D0epSNSiXYq1enVqwHMZlzbMNF8xdCigjIJWTD8Fnc33rEyjPho01eai1ZH3hzUO07oKJKZ_vw1Uab3J0zFMZAg7afgQB7bFiytiqj4CW5aoV_tCvBvzsRf3=w444-h57-s-no-gm?authuser=0"/>
    * The "Use Paints" button is a toggle for whether or not you want the script to consider paints. I recommend not using paints if you plan to build it without the use of cheats.
    <img src="https://lh3.googleusercontent.com/pw/ABLVV87bbuMywoZs0YpM5nf94VytJd2GunHLkB-MKxFR6jn-bSDmF2FHC2cNvzy87Cq80pXCQjC7qIKaYWZdAzWTSvn1ZVZ8lMaBXbmCPIFRELaKIr5884nLBlBTZFmWX3fbw7RQFNh9-4TypLZE8fac1R_h=w447-h72-s-no-gm?authuser=0"/>
    * The "Select Image File" button will prompt you to select the image which you want to use. Generally, its probably a good idea to use an image that is smaller and does not have as many colours. Larger images will take longer to process and will be much larger in-game.
    <img src="https://lh3.googleusercontent.com/pw/ABLVV8728Olhp_LYwkjk4N5gQ_o_G84d7PQ7XUpwXJtEYa71gAR7Loby8Y_4DfZuO0z7rf3uGkslLEJkPLHel-I4skIoXxj0PIRn0elgB7lVt_u0OgfS8_4dGLh8-x5PBCSjNE16y4ZgZsCQ-dwb0hUvwkzc=w444-h58-s-no-gm?authuser=0"/>
    * Finally, "Print File" will process the image and output the data to the text file. The text below will say "completed" when it is done, and the window can be closed.
     <img src="https://lh3.googleusercontent.com/pw/ABLVV86bZW08am3raskXjS2PQo8hGx1Nw8l-mXEkIQWmzSMwOl4CAp-QBzJglRbDAr7QbrYdXEVBY5GTj_qbbIcj448eMSE4KMpQzbm4xS9u8zld4PLUbnxqxVfZSHM2fMAVHcBwHlfaE52uHo5qpwQqEU-y=w446-h89-s-no-gm?authuser=0"/>
 4. After this, the images are ready to be loaded in-game.
 
### Loading Files Ingame

1. Open the mod config via the pause menu. There should be two displayed options.
   * The first field is the directory in which the outputted .txt file is located. 
   <img src="https://lh3.googleusercontent.com/pw/ABLVV87hJqIVKGtq3KjeU6zoo0m6WK-Q5dot-X9LZzEXDIF2IPdG4s-nAKAiXkkmLPx6C9V62pM8eu1w-2jFl4ZpWXp5eWlYcWym6RCMBHLbBVz9S0Qceqil-c6H3SXWoWOL-oRkaVc03Q1WjS5CV-z1Mc7I=w568-h38-s-no-gm?authuser=0"/>
     * Tab out of Terraria and open the extracted folder in file explorer, and right-click the top bar. Then select, "copy address as text", tab back in, and paste the copied text. After doing this, you can save the config.
<img src="https://lh3.googleusercontent.com/pw/ABLVV87WVWqxUNFpqOyedQGgZ8bQy0LV40UGdgqqgfYpr8_xwt9tH1GFM5HiEuXOWdf1FSHgZSruNiEOLRgEwTkIo7KDNz8SQEV7_qbkpzopNKwsMOuU1Pm743HWbKwascFG2GbDyFYd4sD2fX3IBBEE1tce=w1869-h545-s-no-gm?authuser=0"/>
      * I.E. "C:\Users\[Name]\Downloads\Pixel Art Helper"
   * The second option is optional. It toggles a mode which will only display the pixels of the held block. This is useful for if an image requires placing many of the same block, and allows you to do it all at once.
<img src="https://lh3.googleusercontent.com/pw/ABLVV86t0tj5HpQIoEQSBtwr8RQ33NcI039V8RajnJ6Q167-5HdmGifEaRVh150nB49YvZxizEWVB5EPiWPp23jJXAbO3kr8J1HXudv68ktollO4pWU8d-hGDnmFYj0ZV0i25BidqsMypiPaTOvvCEGjG57X=w574-h43-s-no-gm?authuser=0"/>
2. To show the outline on screen, place the cursor where you want the top-left of the image to be, and type "/openHolo [fileName]" in chat (Don't include the .txt). If everything has been done right up to this point, you should see the outline.
<img src="https://lh3.googleusercontent.com/pw/ABLVV84w-ZMBDZwLm26pnqG3yCWVreht7UPtydR8Syf1JqAGxnXGmInMPhAIG7NeJlXYmvTe3wAi2FqMwM9qIa31c8qjcsHE4lCawDH9xkfZ9765RZIomhWx-pDGi0WxtGHfrZDOcGqUWg0uHiYB-VQVVLOp=w178-h36-s-no-gm?authuser=0"/> 
<img src="https://lh3.googleusercontent.com/pw/ABLVV87Cb8FcpJv_ZrCXKcRc0uQPF5i4Wrw80e2Jpdne9yHNJHwtZRyU1uKLHo7aX8d4pfsR0NACIQbOiEuZ11VWSSZYOYYSnJQPw-8kibtjyKtxjipyqDSdxbnRi9xbDljqeUXtPgd_ICJ2mHpTY_7S-R12=w508-h565-s-no-gm?authuser=0" width="200"/>
4. To close it, type "/closeHolo" in the chat.

## What's to come
In the future, I plan on adding an ingame UI which tells the user the remaining blocks which need to be placed in order to complete the pixel art. Coming maybe never.
Potentially also an easier means for doing tile exceptions, perhaps incorporated into the python UI somehow.
