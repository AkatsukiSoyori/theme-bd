</div>

## Theme Editor

You can now customize the theme with a preview before downloading it to your computer.

Please keep in mind that **we do not manage the theme editor**, and cannot help with any bugs that come from using it.

> [Theme Editor](https://bdeditor.dev/theme/)

_Thank you to @Gibbu to providing this._

## Installing

Note: DreamingDragonGirl doesn't actively support plugins (as in, we don't seek out and actively theme fixes to every new plugin). However, when a plugin is widely used, we try our best to stay compatible. 

Download the theme file from [the BetterDiscord Website](URL) or [releases](https://github.com/ClearVision/ClearVision-v6/releases) and move it into your [BetterDiscord](https://betterdiscord.app) themes folder:

## Building from source

To build the theme from source, you can simply run `npm install` to install all missing dependencies and `npm run build` to compile the theme into the `/public` folder.

### Dependencies
- [NodeJS/npm](https://nodejs.org/)
- [sass](https://www.npmjs.com/package/sass)
- [PostCSS Autoprefixer](https://www.npmjs.com/package/autoprefixer)
- [PostCSS CLI](https://www.npmjs.com/package/postcss-cli)
- [rimraf](https://www.npmjs.com/package/rimraf) (for cleanup)
- [Prettier](https://www.npmjs.com/package/prettier) (code formatting)

## Contributing

You can run `npm run test` to compile the theme.
The `main.css` file will be in the `/test` directory, which can then be copied into BetterDiscord's Custom CSS.