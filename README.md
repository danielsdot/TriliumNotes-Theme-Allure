Original Repository of this theme
> Tested on: `TriliumNext 0.100.0` but not complete :)

## Preview
![Screenshot](./resources/screenshot.png)

# Steps by Steps
## Installation
### Easy installation
1. Download `Allure-clear.zip` or `Allure-night.zip` in the release page, then right-click on any note and select "Import to note"
2. Select the file you just downloaded and **uncheck Safe Import**, then click "Import"
> How to upgrade?
> Just delete the theme file and re-import the latest version.
### Manual installation
1. Create a new note in trilium (of type **CSS**) named `Allure-clear` / `Allure-night` *(the name of note depends on which theme you want to apply)*
1. Pick a theme below, copy the content of it and paste it into the new note created above:
    <!-- - [Allure-clear.css](https://github.com/JadeVane/Allure/releases/latest/download/Allure-clear.css) -->
    - [Allure-clear.css](./Allure-clear.css)
    <!-- - [Allure-night.css](https://github.com/JadeVane/Allure/releases/latest/download/Allure-night.css) -->
    - [Allure-night.css](./Allure-night.css)
1. Add `#appTheme=[theme_name]` attribute to the note
1. Download all the fonts in [fonts](./fonts/), then right-click on the note and select `Import to note` to import all fonts
1. Add attribute `#customResourceProvider="font-name.suffix"` to each fonts
> How to upgrade?
> Copy the latest css file content and replace Allure-icon.woff2 in it. If other fonts are updated, other font files also need to be replaced.
## Enable Allure Theme
1. Go to Menu > Options, and select `Allure-clear` / `Allure-night` as your new theme
1. Press `F5` or `Ctrl` + `R` to reload the page
