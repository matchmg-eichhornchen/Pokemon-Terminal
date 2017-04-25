# Pokemon-Terminal

Pokemon terminal themes for iTerm2. Supports a total of 493 unique Pokemon.

![alt-tag](Samples/pikachu.png)

Sample Set #1                    |  Sample Set #2
:-------------------------------:|:-------------------------------:
![alt-tag](Samples/bulbasaur.png)|  ![alt-tag](Samples/squirtle.png)
![alt-tag](Samples/charizard.png)|  ![alt-tag](Samples/eevee.png)
![alt-tag](Samples/clefairy.png) |  ![alt-tag](Samples/magikarp.png)
![alt-tag](Samples/machop.png)   |  ![alt-tag](Samples/slowpoke.png)
![alt-tag](Samples/muk.png)      |  ![alt-tag](Samples/porygon.png)
![alt-tag](Samples/chansey.png)  |  ![alt-tag](Samples/growlithe.png)
![alt-tag](Samples/scyther.png)  |  ![alt-tag](Samples/omanyte.png)
![alt-tag](Samples/corsola.png)  |  ![alt-tag](Samples/mewtwo.png)
![alt-tag](Samples/azumarill.png)|  ![alt-tag](Samples/snubbull.png)
![alt-tag](Samples/wobbuffet.png)|  ![alt-tag](Samples/tyranitar.png)
![alt-tag](Samples/lugia.png)    |  ![alt-tag](Samples/kyogre.png)
![alt-tag](Samples/rayquaza.png) |  ![alt-tag](Samples/deoxys.png)

# Setting Up

To do.

# Usage

```

Usage:
    pokemon [parameter]

Parameters:
    [name]      -   Change the terminal background to the specified Pokemon.
    [index]     -   Change the terminal background to a Pokemon by its index.
    [region]    -   List all the Pokemon of the specified region.
    [letter]    -   List all Pokemon who's names begin with a particular letter.

Other Parameters:
    pokemon all             -   List all the Pokemon supported.
    pokemon random          -   Pick a Pokemon at random.
    pokemon regions         -   List all the available regions.
    pokemon slideshow       -   Iterate through each Pokemon.
    pokemon slideshow-kanto -   Iterate through each Pokemon in the specified reigon.
    pokemon help            -   Display this menu.
    
```

Example:

![alt-tag](Samples/usage.gif)

# Suggestions

I highly suggest making the font colors black and the terminal window transparent. Some of the images have both light and dark colours and so it can be difficult to see the font sometimes. Transparency resolves this issue. Since *Pokemon Terminal* only changes the background, the transparency must be done manually:

1. Navigate to iTerm2 > Preferences > Profiles > Window
2. Set the transparency to the center value.
3. Hit the "blur" checkbox.
4. Set the blur to maximum.

![alt-tag](Samples/transparency_setting.png)

# Solutions for Issues

If you experience a line at the top of the terminal after changing the Pokemon, you can remove it by typing in the *clear* command or opening a new terminal.

![alt-tag](Samples/line.png)
