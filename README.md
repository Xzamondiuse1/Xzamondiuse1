./
├── .editorconfig
├── gulpfile.js
├── package.json
├── README.md
|
├── gulp_tasks/                                * gulp tasks
|   ├── config/                                * gulp tasks config
│   |   ├── paths.js
│   |   └── aliases.js
│   |
|   └── task.js
|
├── screenshots/                               * responsive test screenshots
|
├── dev/                                       * site source
│   ├── images/                                * image sources
|   │
│   ├── pug/                                   * templates
|   |   ├── blocks/                            * blocks library
|   │   |   └── block.pug
|   │   ├── helpers/                           * helper mixins
|   │   ├── vendor/                            * third-party code
|   │   ├── layouts/                           * page layouts
|   │   └── pages/                             * main pages templates
|   │
│   ├── js/                                    * source js
|   |   ├── vendor/                            * vendor scripts library
|   |   ├── lib/                               * site scripts library
|   │   ├── head.js                            * head scripts
|   │   └── body.js                            * body scripts
|   │
|   ├── sass/                                  * sass preprocessor styles
|   |   ├── blocks/                            * blocks library
|   │   |   └── block.sass
|   │   ├── helpers/                           * mixins and vars
|   │   ├── vendor/                            * third-party code
|   │   ├── custom.sass
|   │   ├── noscript.sass
|   │   └── screen.sass
|   │
│   ├── helpers/                               * helper files
|   |   ├── favicon.ico
|   |   └── .htaccess
|   │
│   ├── fonts/                                 * font sources
|   │
│   └── data/                                  * configs and data for templates
│
└── build/                                     * built source
    ├── index.html
    ├── page.html
    |
    └── static/                                * static assets
        ├── css/                               * minified styles
        |
        ├── images/                            * minified images
        │
        ├── js/                                * minified assembled js
        |
        └── fonts/                             * @font-face-ready webfonts
