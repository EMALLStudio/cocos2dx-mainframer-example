# Mainframer integration for cocos2d-x

Tool that allows you to move build process from a local machine to a remote one.

Remote machine ought to be much faster than a laptop.
With `mainframer` you can free up your local machine for better things —
like editing source code in your IDE without lags and
freezes, being able to actually _use_ your computer when the build is happening.

## Installation

- [Setup mainframer](https://github.com/gojuno/mainframer#setup)
- Copy `cocos-mainframer` script

## Usage

- linux remote compile: `./cocos-mainframer compile -p linux`
- linux remote compile & local run: `./cocos-mainframer run -p linux`
- android remote compile: `./cocos-mainframer compile -p android --android-studio`
- android remote compile & local run: `./cocos-mainframer run -p android --android-studio`
