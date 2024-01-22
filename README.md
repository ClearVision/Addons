# Clearvision Addons

Addons created for Clearvision theme. Some might not work properly with other themes, but they should work for most.

Support: [ClearVision Support Server](https://discord.gg/7pNUC9C)

Transparency
------------

Makes your Discord transparent. Maintained by Nyx.
Note: This **REQUIRES** your injector to support transparency. BetterDiscord, Replugged, and Vencord are the 3 clients we provide direct support for that also have transparency. If you are using any other injector, you may not have access to transparency.

### Usage

1.  Copy and paste the following below the other imports

    ```css
    @import url(https://clearvision.github.io/Addons/transparency.css);
    ```
    
2.  Change your --background-image variable to `transparent`:

    ```css
    --background-image: transparent; /* app background image (link must be HTTPS) [default: url(https://clearvision.github.io/images/sapphire.jpg)] */
    ```

3.  Make sure to toggle the background transparency toggle in BetterDiscord settings if you are on that, or any other relevant toggle if you are on another injector that supports transparency.

Gradients
---------

Adds gradients to various parts of the theme to make it more colourful. Maintained by Nyx.

### Usage

1.  Copy and paste the following below the other imports

    ```css
    @import url(https://clearvision.github.io/Addons/gradients.css);
    ```

2.  Add the following at the bottom inside of root:

    ```css
    /* Gradients */
    --gradient-color1: var(--main-color); /* primary color [default: var(--main-color) */
    --gradient-color2: var(--hover-color); /* secondary color [default: var(--hover-color) */
    --gradient-direction: 130deg; /* angle of gradient [default: 130deg] */
    ```

3.  Change the values to customize it and you're done

Old Discord Font
----------------

Use the old discord font, Whitney. Maintained by Nyx, credit to @Overimagine1 for providing the new version of files and script. The old clearvision whitney script is obsolete due to missing characters

### Usage

1.  Copy and paste the following below the other imports

    ```css
    @import url(https://clearvision.github.io/Addons/whitney.css);
    ``` 

2.  Now, change your main-font back to Whitney. This looks like 

    ```css
    --main-font: Whitney, Helvetica Neue, Helvetica, Arial, sans-serif;
    ```

Speech Bubbles
--------------

Displays text in chat as speech bubbbles. Maintained by Leozard ★

### Usage

1.  Copy and paste the following below the other imports

    ```css
    @import url(https://clearvision.github.io/Addons/speech-bubbles.css);
    ```

2.  **Optional:** to change the colors add the following at the bottom inside of root:

    ```css
    /* Speech Bubbbles */
    --bubble-color: #fff;
    --bubble-hover-color: #fff:
    ```
