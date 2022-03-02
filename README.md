# Website

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

## Installation

```console
yarn install
```

## Local Development

```console
yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

## Build

```console
yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Deployment

```console
GIT_USER=<Your GitHub username> USE_SSH=true yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.



## Auto Crop Block Screenshots

If you want to include screenshots of individual blocks or entire block stacks, we have a Photoshop action for you that crops the image automatically and removes the white background.

![Autocrop Action](utilities/photoshop actions/how_to_crop_block_screenshots.png)

### Installation:
you find the necessary files in the folder `utilities/photoshop actions`
1. Install the action Automation Blocks.atn in Photoshop
2. copy the script mm_crop_to_selections.jsx to the folder `Presets/Scripts/` inside the folder of your Photoshop installation (like `/Applications/Adobe Photoshop 2022/Presets/Scripts/` for Ps 2022 on Mac OS, for example)

### Usage
After you opened the screenshot, make sure the only layer it contains is selected and then run the action `Automation Blocks Auto Crop`.


## Retina Images

If you have a High DPI monitor, please make the screenshots in high resolution and save both a file `myImage.png` with normal DPI resolution and `myImage@2x.png` with high DPI resolution.