# Zappar for A-Frame
## Standalone Bootstrap Project

In this project you'll find an `index.html` file that gets you up and running with Zappar for A-Frame.

Head to the NPM package page for more information on how to build best-in-class AR experiences: [Zappar for A-Frame](https://www.npmjs.com/package/@zappar/zappar-aframe) (@zappar/zappar-aframe)

## Preview
Scan the QR code below using your native camera app or QR code reader to view the example:
​
![Preview QR Code"](preview-qr-code.png)


### Local Preview and Testing

Due to browser restrictions surrounding use of the camera, you must use HTTPS to view or preview your site, even if doing so locally from your computer. If you're using `webpack`, consider using `webpack-dev-server` which has an `https` option to enable this.

Alternatively you can use the [ZapWorks command-line tool](https://www.npmjs.com/package/@zappar/zapworks-cli) to serve a folder over HTTPS for access on your local computer, like this:
```
zapworks serve .
```

The command also lets you serve the folder for access by other devices on your local network, like this:
```
zapworks serve . --lan
```

## Target Image
![Target Image](example-tracking-image.png)
