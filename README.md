# cavy_test_framework_setup :  Cavy_integration test framework for React Native

# CAVY Installation :
Install by using yarn  -  yarn add cavy --dev
Install by using npm   -  npm i --save-dev cavy

# ReactNative Sample App (Employee Directory), Installation instructions:- 
//Create a new React Native app named EmployeeDirectory:

react-native init EmployeeDirectory
cd EmployeeDirectory
react-native run-android  / react-native run-ios

//Clone the sample app repository:
git clone https://github.com/ccoenraets/employee-directory-react-native

Copy the app folder from employee-directory-react-native into your EmployeeDirectory project folder

Open index.ios.js. / index.android.js in Editor -  Delete the existing content and replace it with:

import {AppRegistry} from 'react-native';
import EmployeeDirectoryApp from './app/EmployeeDirectoryApp';
AppRegistry.registerComponent('EmployeeDirectory', () => EmployeeDirectoryApp);
