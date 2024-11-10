# ClearVision Addons

Addons created for the ClearVision theme. Some addons might not work properly with other themes but should function well with most.

**Support:** [ClearVision Support Server](https://discord.gg/7pNUC9C)

---

## Table of Contents
- [Addons Overview](#addons-overview)
- [Gradients](#gradients)
- [Server Size](#server-size)
- [Old Discord Font](#old-discord-font)
- [Speech Bubbles](#speech-bubbles)
- [Text Area Underline](#text-area-underline)

---

## Addons Overview <a id="addons-overview"></a>

ClearVision Addons enhance the overall appearance and functionality of the ClearVision theme. Below is an overview of each addon and the changes they introduce:

- **Gradients**: Adds vibrant and customizable gradients to various elements, such as buttons and backgrounds, to give your theme a more dynamic look.
- **Server Size**: Adjusts the size of server icons, allowing you to customize the layout and space used for each server within the theme.
- **Old Discord Font**: Reverts the Discord font to the older "Whitney" font for users who prefer the classic aesthetic.
- **Speech Bubbles**: Transforms chat messages into stylized speech bubbles, providing a fresh, modern look to message bubbles in Discord.
- **Text Area Underline**: Replaces the standard text input outline with a sleek, dynamic underline that follows the color scheme of the theme.

---

## Gradients
<h2 id="gradients">Gradients</h2>
Enhance your theme with **colorful gradients**.  
**Maintained by Nyx**

### Usage

<details>
<summary><strong>Instructions</strong></summary>
<ol>
    <li>Copy and paste the following below the other imports:</li>
    <code>
    @import url(https://clearvision.github.io/Addons/gradients.css);
    </code>
    <li>Add the following at the bottom inside of the <code>:root</code> selector:</li>
    <code>
    /* Gradients */
    --gradient-color1: var(--main-color); /* primary color [default: var(--main-color)] */
    --gradient-color2: var(--hover-color); /* secondary color [default: var(--hover-color)] */
    --gradient-direction: 130deg; /* angle of gradient [default: 130deg] */
    </code>
    <li>Customize the values as needed, and <strong>you're done!</strong></li>
</ol>
</details>

---

## Server Size
<h2 id="server-size">Server Size</h2>
Adjust the server size with a simple variable.  
**Maintained by Nyx**

### Usage

<details>
<summary><strong>Instructions</strong></summary>
<ol>
    <li>Copy and paste the following below the other imports:</li>
    <code>
    @import url(https://clearvision.github.io/Addons/serversize.css);
    </code>
    <li>Add the following at the bottom inside of the <code>:root</code> selector:</li>
    <code>
    /* Server Size */
    --server-size: 48px;
    </code>
    <li>Change the value as needed to customize it, and <strong>you're set!</strong></li>
</ol>
</details>

---

## Old Discord Font
<h2 id="old-discord-font">Old Discord Font</h2>
Revert to the old Discord font, Whitney.  
**Maintained by Nyx**, with credit to **@Overimagine1** for updates.

### Usage

<details>
<summary><strong>Instructions</strong></summary>
<ol>
    <li>Copy and paste the following below the other imports:</li>
    <code>
    @import url(https://clearvision.github.io/Addons/whitney.css);
    </code>
    <li>Change your <code>--main-font</code> back to Whitney:</li>
    <code>
    --main-font: Whitney, Helvetica Neue, Helvetica, Arial, sans-serif;
    </code>
</ol>
</details>

> **Note:** If you already have a Whitney font import, this step may be unnecessary.

---

## Speech Bubbles
<h2 id="speech-bubbles">Speech Bubbles</h2>
Transform your chat text into **speech bubbles** for a fresh look.  
**Maintained by Leozard ★**

### Usage

<details>
<summary><strong>Instructions</strong></summary>
<ol>
    <li>Copy and paste the following below the other imports:</li>
    <code>
    @import url(https://clearvision.github.io/Addons/speech-bubbles.css);
    </code>
    <li><strong>Optional</strong>: Customize the bubble colors by adding this inside the <code>:root</code> selector:</li>
    <code>
    /* Speech Bubbles */
    --bubble-color: #fff;
    --bubble-hover-color: #fff;
    </code>
</ol>
</details>

---

## Text Area Underline
<h2 id="text-area-underline">Text Area Underline</h2>
Replace the default text area outline with an **elegant, dynamic underline**.  
**Maintained by Randymations**

### Usage

<details>
<summary><strong>Instructions</strong></summary>
<ol>
    <li>Copy and paste the following below the other imports:</li>
    <code>
    @import url(https://clearvision.github.io/Addons/textAreaUnderline.css);
    </code>
    <li><strong>Done!</strong> The underline color will respect your <code>--main-color</code>.</li>
</ol>
</details>

---
