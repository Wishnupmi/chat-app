# Aplikasi Chat App dengan Framework 7

![alt text](https://github.com/Wishnupmi/chat-app/blob/main/chat.jpg)

#Channel Youtube Wishnu Programming : 
https://youtube.com/shorts/orWG01veOwo?feature=share

## Framework7 CLI Options

Framework7 app created with following options:

```
{
  "cwd": "C:\\Latihan\\wa",
  "type": [
    "web"
  ],
  "name": "My App",
  "framework": "core",
  "template": "single-view",
  "bundler": "vite",
  "cssPreProcessor": "less",
  "theming": {
    "customColor": false,
    "color": "#007aff",
    "darkTheme": false,
    "iconFonts": true,
    "fillBars": false
  },
  "customBuild": true,
  "customBuildConfig": {
    "rtl": false,
    "darkTheme": true,
    "lightTheme": true,
    "themes": [
      "ios",
      "md",
      "aurora"
    ],
    "components": [
      "appbar",
      "dialog",
      "popup",
      "login-screen",
      "popover",
      "actions",
      "sheet",
      "toast",
      "preloader",
      "progressbar",
      "sortable",
      "swipeout",
      "accordion",
      "contacts-list",
      "virtual-list",
      "list-index",
      "timeline",
      "tabs",
      "panel",
      "card",
      "chip",
      "form",
      "input",
      "checkbox",
      "radio",
      "toggle",
      "range",
      "stepper",
      "smart-select",
      "grid",
      "calendar",
      "picker",
      "infinite-scroll",
      "pull-to-refresh",
      "lazy",
      "data-table",
      "fab",
      "searchbar",
      "messages",
      "messagebar",
      "swiper",
      "photo-browser",
      "notification",
      "autocomplete",
      "tooltip",
      "gauge",
      "skeleton",
      "menu",
      "color-picker",
      "treeview",
      "text-editor",
      "area-chart",
      "pie-chart",
      "elevation",
      "typography"
    ]
  }
}
```

## Install Dependencies

First of all we need to install dependencies, run in terminal
```
npm install
```

## NPM Scripts

* 🔥 `start` - run development server
* 🔧 `dev` - run development server
* 🔧 `build` - build web app for production

## Vite

There is a [Vite](https://vitejs.dev) bundler setup. It compiles and bundles all "front-end" resources. You should work only with files located in `/src` folder. Vite config located in `vite.config.js`.
## Assets

Assets (icons, splash screens) source images located in `assets-src` folder. To generate your own icons and splash screen images, you will need to replace all assets in this directory with your own images (pay attention to image size and format), and run the following command in the project directory:

```
framework7 assets
```

Or launch UI where you will be able to change icons and splash screens:

```
framework7 assets --ui
```



## Documentation & Resources

* [Framework7 Core Documentation](https://framework7.io/docs/)



* [Framework7 Icons Reference](https://framework7.io/icons/)
* [Community Forum](https://forum.framework7.io)

## Support Framework7

Love Framework7? Support project by donating or pledging on:
- Patreon: https://patreon.com/framework7
- OpenCollective: https://opencollective.com/framework7

## Link Demo
https://giflab.my.id/chat-app/index.html
