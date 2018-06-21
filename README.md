# Quasar App

These are the 2 commands needed to be able to build the project:

yarn global add vue-cli
yarn global add quasar-cli

Also run "yarn" inside the directory to make all dependencies are met then run:

quasar dev -m cordova -T android

The above should create a folder called src-cordova/ add the android platform and build the app in dev mode and launch an emulator from android studio. If you already have one running it will use that one.

The addEventListener is located in /src/app.vue in the "mounted" section which according to quasar guarantees that deviceReady has already fired.


