# driftyco/ionic-cli
######

## How to?

### Installation

http://ionicframework.com/docs/cli/install.html
http://ionicframework.com/docs/cli/sass.html

```sh
npm install -g ionic
ionic start ionic-sample --appname "Ionic Sample" --id com.jtom.ionicsample --sass
cd ionic-sample
ionic setup sass
```

### Run in a browser

http://ionicframework.com/docs/cli/start.html
http://ionicframework.com/docs/cli/test.html

```sh
ionic serve --consolelogs --serverlogs
```

### Run on a native platform (Android/iOS)

http://ionicframework.com/docs/cli/run.html

```sh
ionic platform ios
ionic run ios --livereload --consolelogs --serverlogs --debug
```

### Add a logo & splashscreen

http://ionicframework.com/docs/cli/icon-splashscreen.html

```sh
mkdir resources
cp ~/src/slides-ionic-setup/icon.psd ~/src/slides-ionic-setup/splash.psd resources/
ionic resources
```

### Deploy to Ionic View (ionic.io)

http://ionicframework.com/docs/cli/uploading_viewing.html
http://docs.ionic.io/v1.0/docs/view-usage

```sh
ionic login
ionic upload
ionic share jacek@jtom.me
```

### Add some plugin

```sh
ionic plugin add https://github.com/EddyVerbruggen/Flashlight-PhoneGap-Plugin
```

### Debugging

http://docs.ionic.io/v1.0/docs/chrome-inspector

## Problems

- I want to install a plugin only for specific device
- Ionic View is useless in a long run - it has support only for some basic plugins


---


# jtomaszewski/ionic-cordova-gulp-seed
######
