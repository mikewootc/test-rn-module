
# react-native-my-test

## Getting started

`$ npm install react-native-my-test --save`

### Mostly automatic installation

`$ react-native link react-native-my-test`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-my-test` and add `MyTest.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libMyTest.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.ccdt.mod.MyTestPackage;` to the imports at the top of the file
  - Add `new MyTestPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-my-test'
  	project(':react-native-my-test').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-my-test/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-my-test')
  	```


## Usage
```javascript
import MyTest from 'react-native-my-test';

// TODO: What to do with the module?
MyTest;
```
  