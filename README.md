# Android Google Fit and iOS HealthKit

This project contains an example of using iOS HealthKit and Google Fit for Android.

In the example, I am only pulling the Burnt calories for the current week, and showing them on the [Charts](https://www.npmjs.com/package/react-native-gifted-charts). Please feel free to explore other items available in the HealthKit and GoogleFit.

I used [@kingstinct/react-native-healthkit](https://www.npmjs.com/package/@kingstinct/react-native-healthkit) package for iOS HealthKit,
and [react-native-google-fit](https://www.npmjs.com/package/react-native-google-fit) for Google Fit



To run the app on Adroid requires some extra step; please follow the [instructions](https://github.com/StasDoskalenko/react-native-google-fit/blob/HEAD/docs/INSTALLATION.md#demo-walkthrough-development-setup) for additional setup.





## Installation and Testing

clone/download the repo.
cd into the project folder and install `node_modules` by 
```
yarn install
```

to run on iOS we also have to install the pods using 
```
npx pod-install
``` 

Once pods are finished installing, you can run the following commands to run the app

iOS
```
yarn ios
```
Android
```
yarn android
```


If you are facing any problem, just open issue, i will try my best to resolve this issue ASAP. Also you can reach me via [Twitter](https://twitter.com/imhusnain1)


## License
[MIT](https://github.com/husnaintahir/ios-healthkit-googlefit-example/blob/main/LICENSE)