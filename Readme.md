# DeepSpeech Electron example

This is an example of DeepSpeech running in an Electron app with a ReactJS front-end and processing .wav files.

## Run

Run development version (Mac/Linux):

```
npm run dev
```

Run development version (Windows):

```
export BROWSER=none
npm run dev-win
```

## Package

Build distributable package (Mac/Linux):

```
npm run dist
```

Build distributable package (Windows installer):

```
export BROWSER=none
npm run dist-win
```

Test the (dmg/appimage/exe) package file that has been generated in `/dist`.
