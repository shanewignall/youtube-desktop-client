# Youtube Float

> A cross-platform, floating application for viewing Youtube videos

![Screenshot of Tewb](https://github.com/shanewignall/tewb/blob/master/tewb.jpg)

### Install Dependencies

```
$ npm install
```

### Run w/o Building

```
$ npm start
```

### Release
run the "build" script with the "--platform" flag for the desired platform (win32, linux, darwin). For example:

```
$ npm run build -- --platform=win32
```
After this, create an installer from the build by running:
```
$ npm run release
```
You will then have an installer under `/dist/installers/`


Builds the app for macOS, Linux, and Windows, using [electron-packager](https://github.com/electron-userland/electron-packager).

## License

MIT © [Shane Wignall](https://twitter.com/shanemwignall)
