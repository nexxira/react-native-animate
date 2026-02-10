React-Native-Animated-Splash is developed to help the react-native developers in speeding-up their development process. This package leverages the developer in implementing native animations by using our builtin classes for animation with easy to use api, all the animations run on native thread for smooth performance.
##### Objective
The main objective or the edge of this module is that, splash animation runs in parallel with loading of javascript, which means when animation is running, javascript is being loaded in parallel behind the scenes, moreover componentDidMount can also be called for any api hits before calling hide function of splash from react-native side.

### For iOS and Android

### Installation
If you prefer **npm**,
```sh
$ npm install react-native-animated-splash --save
```

If you prefer **yarn**,
```sh
$ yarn add react-native-animated-splash
```
#### For Ios bump deployment version to 12.0+ in Xcode and podfile

```sh
platform :ios, '12.0'
```

#### Also add this line in your podfile

```sh
pod 'RNAnimatedSplash', :path => '../node_modules/react-native-animated-splash'
```
