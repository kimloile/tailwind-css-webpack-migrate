# Tailwind CSS Webpack Migrate Project
This is an example of a super simple Webpack setup for using with Tailwind CSS.

## Installation
To get started, clone the project and install the dependencies:
```
npm install
```

## Project Bundle
After that, start up your Webpack Development Server.
To bundle files with `watch` mode for development which Webpack Development Server will watch files in `assets/src/*` and `tailwind.config.js` config file and rebuild your stylesheet on every change.
```
npm run build-dev
```

To build a production bundle run:
```
npm run build-prod
```
You can play around with `index.html` to see the effects of your changes.

## Add more CSS/JS files
To add more files to get bundled, open file `webpack.variables.js` to enter your input file path, the output file will be located in `assets/dist/*` folder.

## Notes
If there is issue regarding to installing dependencies, try to uninstall/delete the packages in `node-modules` folder and and re-install them.

To uninstall a package you have previously installed locally in the `node_modules` folder, simply delete the folder, or run:
```
npm uninstall <package-name>
```

And re-install the packages, run:
```
npm install
npm rebuild node-sass
```

## Contributing
Have a lot of experience with Tailwind CSS/Webpack and suggestions on how we could improve this template? We'd love a PR!