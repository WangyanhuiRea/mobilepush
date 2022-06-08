
# react-native-mobilepush

## Getting started

`$ npm install react-native-mobilepush --save`

### Mostly automatic installation

`$ react-native link react-native-mobilepush`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-mobilepush` and add `RNMobilepush.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNMobilepush.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNMobilepushPackage;` to the imports at the top of the file
  - Add `new RNMobilepushPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-mobilepush'
  	project(':react-native-mobilepush').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-mobilepush/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-mobilepush')
  	```


## Usage
```javascript
import RNMobilepush from 'react-native-mobilepush';

// TODO: What to do with the module?
RNMobilepush;
```
  