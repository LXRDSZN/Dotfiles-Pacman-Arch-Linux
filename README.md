<article class="markdown-body entry-content container-lg" itemprop="text">
<div align="center" dir="auto">
    <a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/89e05fa7a22bd16e985b9248f1eef40d8638a9a4e570a7eb9b11bbcad28c2b30/68747470733a2f2f617765736f6d65776d2e6f72672f696d616765732f617765736f6d652d6c6f676f2e737667"><img src="https://camo.githubusercontent.com/89e05fa7a22bd16e985b9248f1eef40d8638a9a4e570a7eb9b11bbcad28c2b30/68747470733a2f2f617765736f6d65776d2e6f72672f696d616765732f617765736f6d652d6c6f676f2e737667" data-canonical-src="https://awesomewm.org/images/awesome-logo.svg" style="max-width: 100%;"></a>
</div>
<br>
<div align="center" dir="auto">
    <a target="_blank" rel="noopener noreferrer" href="/Alpharivs/dotfiles/blob/main/.github/assets/awesome.png"><img src="/Alpharivs/dotfiles/raw/main/.github/assets/awesome.png" alt="Rice Preview" style="max-width: 100%;"></a>
</div>
<br>
<br>
<p dir="auto"><a href="https://awesomewm.org/" rel="nofollow"><img alt="AwesomeWM Logo" height="160" align="left" src="https://camo.githubusercontent.com/a682e524f55880d0f58f95cb6008a01b74493036b71cb121ac7112429400a0dc/68747470733a2f2f617765736f6d65776d2e6f72672f646f632f6170692f696d616765732f4155544f47454e5f7769626f785f6c6f676f5f6c6f676f5f616e645f6e616d652e737667" data-canonical-src="https://awesomewm.org/doc/api/images/AUTOGEN_wibox_logo_logo_and_name.svg" style="max-width: 100%;"></a>
<b>  Aesthetic AwesomeWM Dotfiles  </b></p>
<p dir="auto">Welcome to my AwesomeWM configuration files!</p>
<p dir="auto">so yeah now i'm using awesomewm, looks like i'll be use this wm forever.</p>
<p dir="auto">Because only this wm can satisfy me.</p>
<p dir="auto">Fyi, I use night colorscheme, and it's so beautiful.</p>
<p dir="auto">These dotfiles are made with love, for sure.</p>
<h2 dir="auto"></h2><br>
<p dir="auto"><strong>Here are some details about my setup:</strong></p>
<table>
<thead>
<tr>
<th>Programs</th>
<th>Using</th>
</tr>
</thead>
<tbody>
<tr>
<td>WM</td>
<td>awesome</td>
</tr>
<tr>
<td>OS</td>
<td>arch linux</td>
</tr>
<tr>
<td>Terminal</td>
<td>alacritty</td>
</tr>
<tr>
<td>Shell</td>
<td>zsh</td>
</tr>
<tr>
<td>Editor</td>
<td>neovim / vscode</td>
</tr>
<tr>
<td>Compositor</td>
<td>picom</td>
</tr>
<tr>
<td>Launcher</td>
<td>rofi</td>
</tr>
</tbody>
</table>
<h2 dir="auto"></h2><br>
<details>
<summary><strong>S E T U P</strong></summary>
<blockquote>
<p dir="auto">This is step-by-step how to install these dotfiles. Just <a href="https://en.wikipedia.org/wiki/RTFM" rel="nofollow">R.T.F.M</a>.</p>
</blockquote>
<ol dir="auto">
<li>
<p dir="auto">Install dependencies and enable services</p>
<ul dir="auto">
<li>Dependencies</li>
</ul>
<ul dir="auto">
<li>
<p dir="auto"><strong>Arch Linux</strong> (and all Arch-based distributions)</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>*Assuming your AUR helper is* `yay`

```shell
yay -Sy awesome-git picom-git alacritty rofi todo-bin acpi acpid \
wireless_tools jq inotify-tools polkit-gnome xdotool xclip maim \
brightnessctl alsa-utils alsa-tools pulseaudio lm_sensors \
mpd mpc mpdris2 ncmpcpp playerctl --needed 
```
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="*Assuming your AUR helper is* `yay`

```shell
yay -Sy awesome-git picom-git alacritty rofi todo-bin acpi acpid \
wireless_tools jq inotify-tools polkit-gnome xdotool xclip maim \
brightnessctl alsa-utils alsa-tools pulseaudio lm_sensors \
mpd mpc mpdris2 ncmpcpp playerctl --needed 
```" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
</ul>
<ul dir="auto">
<li>
<p dir="auto">Services</p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> For automatically launching mpd on login</span>
systemctl --user <span class="pl-c1">enable</span> mpd.service
systemctl --user start mpd.service

<span class="pl-c"><span class="pl-c">#</span> For charger plug/unplug events (if you have a battery)</span>
sudo systemctl <span class="pl-c1">enable</span> acpid.service
sudo systemctl start acpid.service</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# For automatically launching mpd on login
systemctl --user enable mpd.service
systemctl --user start mpd.service

# For charger plug/unplug events (if you have a battery)
sudo systemctl enable acpid.service
sudo systemctl start acpid.service" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
</ul>
</li>
<li>
<p dir="auto">Install needed fonts</p>
<p dir="auto">You will need to install a few fonts (mainly icon fonts) in order for text and icons to be rendered properly.</p>
<p dir="auto">Necessary fonts:</p>
<ul dir="auto">
<li><strong>Iosevka</strong>  - <a href="https://github.com/ryanoasis/nerd-fonts/">here</a></li>
<li><strong>Icomoon</strong>  - <a href="https://www.dropbox.com/s/hrkub2yo9iapljz/icomoon.zip?dl=0" rel="nofollow">here</a></li>
<li><strong>Material</strong> - <a href="https://github.com/google/material-design-icons">here</a></li>
</ul>
<p dir="auto">Once you download them and unpack them, place them into <code>~/.fonts</code> or <code>~/.local/share/fonts</code>.</p>
</li>
<li>
<p dir="auto">Install my AwesomeWM configuration files</p>
<blockquote>
<p dir="auto">Clone this repository</p>
</blockquote>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>git clone https://github.com/rxyhn/dotfiles.git
<span class="pl-c1">cd</span> dotfiles</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="git clone https://github.com/rxyhn/dotfiles.git
cd dotfiles" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<blockquote>
<p dir="auto">Copy config and binaries files</p>
</blockquote>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>cp -r config/<span class="pl-k">*</span> <span class="pl-k">~</span>/.config/
cp -r bin/<span class="pl-k">*</span> <span class="pl-k">~</span>/.local/bin/
cp -r misc/. <span class="pl-k">~</span>/</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="cp -r config/* ~/.config/
cp -r bin/* ~/.local/bin/
cp -r misc/. ~/" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<blockquote>
<p dir="auto">You have to add <code>TODO_PATH</code> in your env variable</p>
</blockquote>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">export</span> TODO_PATH=<span class="pl-s"><span class="pl-pds">"</span>path/to/todo<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="export TODO_PATH=&quot;path/to/todo&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto">Configure stuff</p>
<p dir="auto">The relevant files are inside your <code>~/.config/awesome</code> directory.</p>
<ul dir="auto">
<li>
<p dir="auto">User preferences and default applications</p>
<p dir="auto">In <code>rc.lua</code> there is a <em>Default Applications</em> section where user preferences and default applications are defined.
You should change those to your liking.</p>
<p dir="auto">Note: For the weather widgets to work, you will also need to create an account on <a href="https://openweathermap.org" rel="nofollow">openweathermap</a>, get your key, look for your city ID, and set <code>openweathermap_key</code> and <code>openweathermap_city_id</code> accordingly.</p>
</li>
</ul>
</li>
<li>
<p dir="auto">Lastly, log out from your current desktop session and log in into AwesomeWM.</p>
</li>
</ol>
</details>
<br>
<details>
<summary><strong>F E A T U R E S</strong></summary>
<p dir="auto"><b>These are the features included in my AwesomeWM setups!</b></p>
<ul dir="auto">
<li>Beautiful <code>colorscheme</code> ikr, named <code>night</code> and created by <a href="https://github.com/ner0z">ner0z</a></li>
<li>Aesthetic <code>Dashboard</code> ngl.</li>
<li>Custom mouse-friendly <code>ncmpcpp</code> UI with album art ofc.
<ul dir="auto">
<li>
<details>
 <summary>Preview</summary>
<p dir="auto"><em>this is so aesthetic isn't it?</em></p>
 <div align="left" dir="auto">
 <a target="_blank" rel="noopener noreferrer" href="/Alpharivs/dotfiles/blob/main/.github/assets/ncmpcpp.png"><img src="/Alpharivs/dotfiles/raw/main/.github/assets/ncmpcpp.png" width="500px" alt="ncmpcpp preview" style="max-width: 100%;"></a>
 </div>
 </details>
</li>
</ul>
</li>
<li><code>Word Clock Lockscreen</code> with PAM Integration
<ul dir="auto">
<li>
<details>
<p dir="auto"><em>A beautiful word clock is on the lockscreen!</em></p>
 <summary>Preview</summary>
 <div align="left" dir="auto">
 <a target="_blank" rel="noopener noreferrer" href="/Alpharivs/dotfiles/blob/main/.github/assets/lockscreen.png"><img src="/Alpharivs/dotfiles/raw/main/.github/assets/lockscreen.png" width="500px" alt="word clock lockscreen preview" style="max-width: 100%;"></a>
 </div>
 </details>
</li>
</ul>
</li>
<li>Notification Center</li>
<li>Control Panel</li>
<li>ToDo Reminder</li>
<li>Battery Indicator</li>
<li>PopUp Notifications</li>
<li>Applications Launcher</li>
<li>Some Tooltip Widget</li>
<li>Hardware Monitor</li>
</ul>
</details>
<br>
<details>
<summary><strong>K E Y B I N D S</strong></summary>
<p dir="auto">I use <kbd>super</kbd> AKA Windows key as my main modifier.
also with <kbd>alt, shift, and ctrl</kbd></p>
<p dir="auto"><strong>Keyboard</strong></p>
<table>
<thead>
<tr>
<th>Keybind</th>
<th>Action</th>
</tr>
</thead>
<tbody>
<tr>
<td><kbd>super + enter</kbd></td>
<td>Spawn terminal</td>
</tr>
<tr>
<td><kbd>super + w</kbd></td>
<td>Spawn web browser</td>
</tr>
<tr>
<td><kbd>super + x</kbd></td>
<td>Spawn color picker</td>
</tr>
<tr>
<td><kbd>super + f</kbd></td>
<td>Spawn file manager</td>
</tr>
<tr>
<td><kbd>super + d</kbd></td>
<td>Launch applications launcher</td>
</tr>
<tr>
<td><kbd>super + shift + d</kbd></td>
<td>Toggle dashboard</td>
</tr>
<tr>
<td><kbd>super + q</kbd></td>
<td>Close client</td>
</tr>
<tr>
<td><kbd>super + ctrl + l</kbd></td>
<td>Toggle lock screen</td>
</tr>
<tr>
<td><kbd>super + [1-0]</kbd></td>
<td>View tag AKA change workspace (for you i3/bsp folks)</td>
</tr>
<tr>
<td><kbd>super + shift + [1-0]</kbd></td>
<td>Move focused client to tag</td>
</tr>
<tr>
<td><kbd>super + space</kbd></td>
<td>Select next layout</td>
</tr>
<tr>
<td><kbd>super + s</kbd></td>
<td>Set tiling layout</td>
</tr>
<tr>
<td><kbd>super + shift + s</kbd></td>
<td>Set floating layout</td>
</tr>
<tr>
<td><kbd>super + c</kbd></td>
<td>Center floating client</td>
</tr>
<tr>
<td><kbd>super + [arrow keys]</kbd></td>
<td>Change focus by direction</td>
</tr>
<tr>
<td><kbd>super + shift + f</kbd></td>
<td>Toggle fullscreen</td>
</tr>
<tr>
<td><kbd>super + m</kbd></td>
<td>Toggle maximize</td>
</tr>
<tr>
<td><kbd>super + n</kbd></td>
<td>Minimize</td>
</tr>
<tr>
<td><kbd>ctrl + shift + n</kbd></td>
<td>Restore minimized</td>
</tr>
<tr>
<td><kbd>alt + tab</kbd></td>
<td>Window switcher</td>
</tr>
</tbody>
</table>
<br>
<p dir="auto"><strong>Mouse on the desktop</strong></p>
<table>
<thead>
<tr>
<th>Mousebind</th>
<th>Action</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>left click</code></td>
<td>Dismiss all notifications</td>
</tr>
<tr>
<td><code>right click</code></td>
<td>App drawer</td>
</tr>
<tr>
<td><code>middle click</code></td>
<td>Toggle Dashboard</td>
</tr>
<tr>
<td><code>scroll up/down</code></td>
<td>Cycle through tags</td>
</tr>
</tbody>
</table>
<p dir="auto"><em>... And many many more! for more information check <code>awesome/configuration/keys.lua</code></em></p>
</details>
<h2 dir="auto"></h2><br>
<p dir="auto"><strong>Acknowledgements</strong></p>
<ul dir="auto">
<li>
<p dir="auto"><strong>Credits</strong></p>
<ul dir="auto">
<li><a href="https://github.com/ner0z">ner0z</a></li>
</ul>
</li>
<li>
<p dir="auto"><strong>Special thanks to</strong></p>
<ul dir="auto">
<li><a href="https://github.com/ChocolateBread799">ChocolateBread799</a></li>
<li><a href="https://github.com/JavaCafe01">JavaCafe01</a></li>
</ul>
</li>
</ul>
<h2 dir="auto"></h2><br>
<p align="center" dir="auto"><a href="https://github.com/rxyhn/AwesomeWM-Dotfiles/blob/main/.github/LICENSE"><img src="https://camo.githubusercontent.com/c6ef007ff80d4d159e514aab518a96d2867a623ffcfd8639c2438c800fadd45f/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76312e7376673f7374796c653d666c61742d737175617265266c6162656c3d4c6963656e7365266d6573736167653d47504c2d332e30266c6f676f436f6c6f723d656365666634266c6f676f3d67697468756226636f6c6f72413d30363131313526636f6c6f72423d363741464331" data-canonical-src="https://img.shields.io/static/v1.svg?style=flat-square&amp;label=License&amp;message=GPL-3.0&amp;logoColor=eceff4&amp;logo=github&amp;colorA=061115&amp;colorB=67AFC1" style="max-width: 100%;"></a></p>
</article>
