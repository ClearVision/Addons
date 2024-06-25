# Clearvision Addons

Addons created for Clearvision theme. Some might not work properly with other themes, but they should work for most.

Support: [ClearVision Support Server](https://discord.gg/7pNUC9C)

# Table of Contents
- [Clearvision Addons](#clearvision-addons)
- [Table of Contents](#table-of-contents)
- [Gradients](#gradients)
    - [Usage](#usage)
- [Server Size - currently not working due to reroll](#server-size---currently-not-working-due-to-reroll)
    - [Usage](#usage-1)
- [Old Discord Font](#old-discord-font)
    - [Usage](#usage-2)
- [Speech Bubbles - currently not working due to reroll](#speech-bubbles---currently-not-working-due-to-reroll)
    - [Usage](#usage-3)
- [Text Area Underline - currently not working due to reroll](#text-area-underline---currently-not-working-due-to-reroll)
    - [Usage](#usage-4)

# Gradients

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

# Server Size - currently not working due to reroll

Adds a server size variable. Pings start to have a little trouble when you set the value lower than 48px, the discord default. Maintained by Nyx.

### Usage

1.  Copy and paste the following below the other imports

    ```css
    @import url(https://clearvision.github.io/Addons/serversize.css);
    ```

2.  Add the following at the bottom inside of root:

    ```css
    /* Server Size */
    --server-size: 48px;
    ```

3.  Change the value to customize it and you're done

# Old Discord Font

Use the old discord font, Whitney. Maintained by Nyx, credit to @Overimagine1 for providing the new version of files and script. The old clearvision whitney script is obsolete due to missing characters. Note that this addon works just by importing the font, just like any other font import; thus if you have another font import that happens to have whitney, you don't need this.

### Usage

1.  Copy and paste the following below the other imports

    ```css
    @import url(https://clearvision.github.io/Addons/whitney.css);
    ``` 

2.  Now, change your main-font back to Whitney. This looks like 

    ```css
    --main-font: Whitney, Helvetica Neue, Helvetica, Arial, sans-serif;
    ```

# Speech Bubbles

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

# Text Area Underline - currently not working due to reroll

Replaces the default text area outline with a dynamic underline on hover or focus. Maintained by Randymations.

### Usage

1.  Copy and paste the following below the other imports

    ```css
    @import url(https://clearvision.github.io/Addons/textAreaUnderline.css);
    ```

2.  You're done! The color of the underline respects your `--main-color`.
