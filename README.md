
# ClearVision Addons

Addons created for the ClearVision theme. Some addons might not work properly with other themes but should function well with most.

**Support:** [ClearVision Support Server](https://discord.gg/7pNUC9C)

---

## Table of Contents
- [ClearVision Addons](#clearvision-addons)
- [Table of Contents](#table-of-contents)
- [Gradients](#gradients)
    - [Usage](#usage)
- [Server Size](#server-size)
    - [Usage](#usage-1)
- [Old Discord Font](#old-discord-font)
    - [Usage](#usage-2)
- [Speech Bubbles](#speech-bubbles)
    - [Usage](#usage-3)
- [Text Area Underline](#text-area-underline)
    - [Usage](#usage-4)

---

## Gradients

Enhance your theme with <mark>colorful gradients</mark>. **Maintained by Nyx**.

### <ins>Usage</ins>

<details>
<summary><strong>Instructions</strong></summary>
<ol>
    <li>Copy and paste the following below the other imports:<br><br>

    ```css
    @import url(https://clearvision.github.io/Addons/gradients.css);
    ```<br>

    </li>
    <li>Add the following at the bottom inside of the <code>:root</code> selector:<br><br>

    ```css
    /* Gradients */
    --gradient-color1: var(--main-color); /* primary color [default: var(--main-color)] */
    --gradient-color2: var(--hover-color); /* secondary color [default: var(--hover-color)] */
    --gradient-direction: 130deg; /* angle of gradient [default: 130deg] */
    ```<br>

    </li>
    <li>Customize the values as needed, and <strong>you're done!</strong></li>
</ol>
</details>

---

## Server Size

Adjust the server size with a simple variable. <strong>Maintained by Nyx</strong>.

### <ins>Usage</ins>

<details>
<summary><strong>Instructions</strong></summary>
<ol>
    <li>Copy and paste the following below the other imports:<br><br>

    ```css
    @import url(https://clearvision.github.io/Addons/serversize.css);
    ```<br>

    </li>
    <li>Add the following at the bottom inside of the <code>:root</code> selector:<br><br>

    ```css
    /* Server Size */
    --server-size: 48px;
    ```<br>

    </li>
    <li>Change the value as needed to customize it, and <strong>you're set!</strong></li>
</ol>
</details>

---

## Old Discord Font

Revert to the old Discord font, Whitney. <strong>Maintained by Nyx</strong>, with credit to <strong>@Overimagine1</strong> for updates.

### <ins>Usage</ins>

<details>
<summary><strong>Instructions</strong></summary>
<ol>
    <li>Copy and paste the following below the other imports:<br><br>

    ```css
    @import url(https://clearvision.github.io/Addons/whitney.css);
    ```<br>

    </li>
    <li>Change your <code>--main-font</code> back to Whitney:<br><br>

    ```css
    --main-font: Whitney, Helvetica Neue, Helvetica, Arial, sans-serif;
    ```<br>

    </li>
</ol>
</details>

<mark>Note:</mark> If you already have a Whitney font import, this step may be unnecessary.

---

## Speech Bubbles

Transform your chat text into <mark>speech bubbles</mark> for a fresh look. **Maintained by Leozard ★**.

### <ins>Usage</ins>

<details>
<summary><strong>Instructions</strong></summary>
<ol>
    <li>Copy and paste the following below the other imports:<br><br>

    ```css
    @import url(https://clearvision.github.io/Addons/speech-bubbles.css);
    ```<br>

    </li>
    <li><strong>Optional</strong>: Customize the bubble colors by adding this inside the <code>:root</code> selector:<br><br>

    ```css
    /* Speech Bubbles */
    --bubble-color: #fff;
    --bubble-hover-color: #fff;
    ```<br>

    </li>
</ol>
</details>

---

## Text Area Underline

Replace the default text area outline with an <mark>elegant, dynamic underline</mark>. **Maintained by Randymations**.

### <ins>Usage</ins>

<details>
<summary><strong>Instructions</strong></summary>
<ol>
    <li>Copy and paste the following below the other imports:<br><br>

    ```css
    @import url(https://clearvision.github.io/Addons/textAreaUnderline.css);
    ```<br>

    </li>
    <li><strong>Done!</strong> The underline color will respect your <code>--main-color</code>.</li>
</ol>
</details>

---
