<div align="center">
  <h1> Aesthetic Start page </h1>
  <i> A distraction free, customizable startpage. </i>
</div>

<br>

<p align="center">
Discover a visually captivating and customizable browser startpage designed to elevate your browsing experience and productivity. This sleek platform offers a range of default themes to match your style, along with a toggleable night-mode for comfortable nighttime browsing. With a personalized search bar, you can easily choose your preferred search engine.
</p>

<hr>

## Features
- Minimal and stays out of your way, whilst being useful.
- **Customizable Search Bar:** Search the web using your preferred search engine. Easily switch between search engines by typing `:search <search_engine>` in the input box. All other strings will search the web using the currently selected search engine. Search engines to choose from:
  - `google`
  - `bing`
  - `ddg`
- **Multiple Themes:** Choose from 3 beautiful default themes, offering unique aesthetics and styles. To switch themes, type `:theme <theme>` in the input box. Themes to choose from:
  - `catp` ([Catppuccin](https://github.com/catppuccin/catppuccin))
  - `aqua` ([Aquarium](https://github.com/FrenzyExists/aquarium-vim))
  - `light` ([Nord](https://www.nordtheme.com/))
  - `dark` (defaults to `aqua`)
- **Quick Access Links:** Conveniently placed beneath the search bar, these links provide easy access to your most frequently visited websites, acting as a lightweight bookmark system.


## Installation

Clone or download this repository.

```bash
git clone https://github.com/yuuushio/Browser-Startpage.git
```

#### Chromium Browsers:

- Load the startpage as an unpacked extension:
  - Navigate to `chrome://extensions` in your browser.
  - Enable "Developer mode" using the toggle in the top-right corner.
  - Click "Load unpacked" and select the folder cloned repo folder.
  - The startpage will now be set as your new tab page.

#### Firefox
- Go to `about:addons` or select "Add-ons and Themes" from menu bar.
- Click the gear icon.
- Select "Install Add-on From File" from dropdown.
- Locate the cloned repo and select the `.xpi` file.

## Customization

You can further customize the startpage to match your preferences by modifying the `index.html`, `style.css`, and `script.js` files.
- Add or remove quick access links by editing the index.html file.
- Add new **themes**, features or modify existing ones by editing the `script.js` file (because I want to be able to change the side image along with the theme).