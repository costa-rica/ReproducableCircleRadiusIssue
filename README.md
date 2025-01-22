# Issue for react-native-svg <Circle/> "r" mis-assignment

This is a repo for a reproducable example of the <Circle/> component not correctly rendering the radius but instead the diameter

## install

`yarn add react-native-svg`

## Steps to reproduce from this repo

1. clone repo
2. `yarn install`
3. `yarn start`
4. run app on emulator or device
5. Notice that in the terminal the logged width is 200 even though the r (radius) property is set to 100, indicating that the r value behaves as a diameter rather than a radius.

## Here is a screen shot with blue arrow pointing to issue

![screenShotOfIssue](/docs/screenShotWithArrows.png)
