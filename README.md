# Obsidian Enhance Navigate Pane

An Obsidian plugin that superpowers your native File Explorer (Navigate Pane) with advanced features like inline heading navigation, powerful filtering, custom icons, and extensive appearance customization.

## Features

### 🔍 Advanced Filtering & Search
- **Filter Textbox:** Adds a highly responsive search bar directly to the top of the File Explorer.
- **Heading Search:** Search doesn't just find files and folders; it can also match markdown headings inside your files! 
- **Tree Hierarchy Preservation:** When a nested file or heading matches your search, the plugin displays the complete folder and heading structure above it, ensuring you never lose context.
- **Highlight Matches:** Search results are beautifully highlighted (soft yellow background, black text) for maximum readability.

### 📑 Headings Navigation
- **Inline Headings:** View your markdown headings (H1-H6) directly underneath the files in the File Explorer. Click any heading to instantly jump to that exact line in the document.
- **Limit Heading Depth:** Choose the maximum heading level to display (e.g., only show up to H3).
- **Auto-expand:** Automatically expand the heading tree down to a specific level when opening or viewing a file.
- **Smart Expansion:** Configure what happens when you click a heading's collapse arrow: expand only the "Next level" or expand "All levels" at once.

### 🖱️ Workflow Enhancements
- **Recursive Collapse:** When enabled, collapsing a folder, file, or heading will automatically collapse all of its nested children. No more messy, fully-expanded trees when you reopen a folder!
- **Intercept Mouse Click:** If you prefer using the keyboard or don't want to accidentally open files, this feature prevents a single click from opening a file. A single click will only select/highlight the file, requiring a double-click (or pressing Enter) to actually open it.

### 🎨 Appearance & UI Customization
Make your File Explorer look exactly the way you want.
- **Icon Sets:** Add beautiful file and folder icons to your explorer. Choose from **Material Icons**, **VSCode Icons**, **Phosphor Icons**, or **Lucide Icons** (or stick to the default Obsidian look).
- **Font Size:** Adjust the text size specifically for the File Explorer.
- **Item Padding & Margin:** Tweak the spacing around files and folders for a more compact or spacious look.
- **Tree Indentation:** Precisely control the indentation width for nested files and folders.

## Installation

### Manual Installation
1. Download the latest release from the GitHub releases page.
2. Extract the files (`main.js`, `manifest.json`, `styles.css`) into your Obsidian vault's plugins folder: `[Vault]/.obsidian/plugins/obsidian-plugins-enhance-navigate-pane/`
3. Restart Obsidian and enable the plugin in `Settings -> Community Plugins`.

## Settings Guide

- **General:** Toggle the Filter Textbox, Intercept Mouse Click, and the new Recursive Collapse feature.
- **Appearance:** Select your preferred Icon Set, and manually tweak Font Size, Padding, Margin, and Tree Indentation to fit your theme.
- **Headings Navigation:** Enable/disable heading display, set the maximum depth, auto-expand settings, and configure arrow expansion behavior.

---

## ❤️ Support & Donate

If this plugin has improved your Obsidian workflow, saved you time, or you just want to support its continued development, please consider donating! 

Your support is incredibly appreciated, helps fix bugs, and keeps this project alive and growing. 🙏

https://buymeacoffee.com/endofday

<a href="https://www.buymeacoffee.com/endofday" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

---
**Built with ❤️ for the Obsidian Community**
