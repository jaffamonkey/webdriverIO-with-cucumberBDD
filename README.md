### Prerequisites

Ensure you have Java JDK 9 installed
Ensure you have Xcode installed
Set node version at least 6.10.2
Install Android Studio

#### Node version management

To switch node versions, do the following from Terminal:

sudo npm cache clean -f
sudo npm install -g n
sudo n 6.10.2
Then run the following from Terminal.

cd /Library/Java/JavaVirtualMachines/jdk-9.jdk/Contents/Home
sudo ln -s ./ jre`

## Installation

npm install

## Start Appium and Emulator

* ./node_modules/.bin/appium 
* List emulators: /Users/{User}/Library/Android/sdk/tools/emulator -list-avds
* Start emulator:  /Users/{User}/Library/Android/sdk/tools/emulator -avd Nexus_5X_API_27_x86 -netdelay none -netspeed full

## Run tests
### Run browser tests

* npm run test

### Run mobile tests

* npm run tests-mobile (mobile tests)