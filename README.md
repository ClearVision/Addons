<h1> ClearVision Addons </h1>

<p> Addons created for the ClearVision theme. Some addons might not work properly with other themes but should function well with most. </p>

<p><strong>Support:</strong> <a href="https://discord.gg/7pNUC9C">ClearVision Support Server</a></p>

<hr>

<h2>Table of Contents</h2>
<ul>
  <li><a href="#addons-overview">Addons Overview</a></li>
  <li><a href="#gradients">Gradients</a> | <a href="#gradients-usage">Usage</a></li>
  <li><a href="#server-size">Server Size</a> | <a href="#server-size-usage">Usage</a></li>
  <li><a href="#old-discord-font">Old Discord Font</a> | <a href="#old-discord-font-usage">Usage</a></li>
  <li><a href="#speech-bubbles">Speech Bubbles</a> | <a href="#speech-bubbles-usage">Usage</a></li>
  <li><a href="#text-area-underline">Text Area Underline</a> | <a href="#text-area-underline-usage">Usage</a></li>
</ul>

<hr>

<h2 id="addons-overview">Addons Overview</h2>

<p>ClearVision Addons enhance the overall appearance and functionality of the ClearVision theme. Below is an overview of each addon and the changes they introduce:</p>

<ul>
  <li><strong>Gradients:</strong> Adds vibrant and customizable gradients to various elements, such as buttons and backgrounds, to give your theme a more dynamic look.</li>
  <li><strong>Server Size:</strong> Adjusts the size of server icons, allowing you to customize the layout and space used for each server within the theme.</li>
  <li><strong>Old Discord Font:</strong> Reverts the Discord font to the older "Whitney" font for users who prefer the classic aesthetic.</li>
  <li><strong>Speech Bubbles:</strong> Transforms chat messages into stylized speech bubbles, providing a fresh, modern look to message bubbles in Discord.</li>
  <li><strong>Text Area Underline:</strong> Replaces the standard text input outline with a sleek, dynamic underline that follows the color scheme of the theme.</li>
</ul>

<hr>

<h2 id="gradients">Gradients</h2>
<p>Enhance your theme with <strong>colorful gradients</strong>.</p>
<p><strong>Maintained by <a href="https://github.com/NyxIsBad">Nyx</a></strong></p>

<details>
  <summary>Usage</summary>
  <a id="gradients-usage"></a>
  <pre><code>
@import url(https://clearvision.github.io/Addons/gradients.css);
</code></pre>

  <p>Add the following at the bottom inside of the <code>:root</code> selector:</p>

  <pre><code>
/* Gradients */
--gradient-color1: var(--main-color); /* primary color [default: var(--main-color)] */
--gradient-color2: var(--hover-color); /* secondary color [default: var(--hover-color)] */
--gradient-direction: 130deg; /* angle of gradient [default: 130deg] */
</code></pre>

  <p>Customize the values as needed, and <strong>you're done!</strong></p>
</details>

<hr>

<h2 id="server-size">Server Size</h2>
<p>Adjust the server size with a simple variable.</p>
<p><strong>Maintained by <a href="https://github.com/NyxIsBad">Nyx</a></strong></p>

<details>
  <summary>Usage</summary>
  <a id="server-size-usage"></a>
  <pre><code>
@import url(https://clearvision.github.io/Addons/serversize.css);
</code></pre>

  <p>Add the following at the bottom inside of the <code>:root</code> selector:</p>

  <pre><code>
/* Server Size */
--server-size: 48px;
</code></pre>

  <p>Change the value as needed to customize it, and <strong>you're set!</strong></p>
</details>

<hr>

<h2 id="old-discord-font">Old Discord Font</h2>
<p>Revert to the old Discord font, Whitney.</p>
<p><strong>Maintained by <a href="https://github.com/Overimagine1">Nyx</a>, with credit to <a href="https://github.com/Overimagine1">Overimagine1</a> for updates.</strong></p>

<details>
  <summary>Usage</summary>
  <a id="old-discord-font-usage"></a>
  <pre><code>
@import url(https://clearvision.github.io/Addons/whitney.css);
</code></pre>

  <p>Change your <code>--main-font</code> back to Whitney:</p>

  <pre><code>
--main-font: Whitney, Helvetica Neue, Helvetica, Arial, sans-serif;
</code></pre>

  <p><em>Note:</em> If you already have a Whitney font import, this step may be unnecessary.</p>
</details>

<hr>

<h2 id="speech-bubbles">Speech Bubbles</h2>
<p>Transform your chat text into <strong>speech bubbles</strong> for a fresh look.</p>
<p><strong>Maintained by <a href="https://github.com/Leozard">Leozard</a> ★</strong></p>

<details>
  <summary>Usage</summary>
  <a id="speech-bubbles-usage"></a>
  <pre><code>
@import url(https://clearvision.github.io/Addons/speech-bubbles.css);
</code></pre>

  <p><strong>Optional:</strong> Customize the bubble colors by adding this inside the <code>:root</code> selector:</p>

  <pre><code>
/* Speech Bubbles */
--bubble-color: #fff;
--bubble-hover-color: #fff;
</code></pre>
</details>

<hr>

<h2 id="text-area-underline">Text Area Underline</h2>
<p>Replace the default text area outline with an <strong><ins>elegant, dynamic underline</strong></ins>.</p>
<p><strong>Maintained by <a href="https://github.com/randymations">Randymations</a></strong></p>

<details>
  <summary>Usage</summary>
  <a id="text-area-underline-usage"></a>
  <pre><code>
@import url(https://clearvision.github.io/Addons/textAreaUnderline.css);
</code></pre>

  <p><strong>Done!</strong> The underline color will respect your <code>--main-color</code>.</p>
</details>

<hr>
