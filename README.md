# UpContent Theme Preview

To submit your whitelabel theme colors fork this repo and than modify the theme.scss appropriately. Once it is to your liking send us a link to the forked repo and we'll handle getting it into UpContent.

## Installation
After cloning run ensure you have yarn installed (`npm install -g yarn`). Then run
```shell
yarn install
```
If you run into any issues with node versions and want to use the same one it was built with this was originally built using node 14.

## Creating your theme
To create your theme simply modify the SCSS variables in theme.scss.

## Previewing
To build the theme and preview run the following command than open one of the links in the output in your browser 
```shell
yarn serve
```

This is a pretty simple build chain so you'll need to re-run the serve command (or build command below) every time you make changes

If you prefer to use a different web server such as your built in IDE web server you can instead simply run `yarn build`

## Images
You don't need to have your images sorted out for your first submission for a good preview but prior to going to go live if you want any images replaced with specific images please replace the images in the images folder as well.
