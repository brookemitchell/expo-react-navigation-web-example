How to run:

`npm install`
`npm run web`

Currently you should see the error 

```
TypeError: Cannot assign to read only property 'exports' of object '#<Object>'
Module.<anonymous>
node_modules/react-native-gesture-handler/GestureHandler.js:578
  575 |   ));
  576 | }
  577 | 
> 578 | module.exports = {
  579 |   /* RN's components */
  580 |   get ScrollView() {
  581 |     return memoizeWrap(ReactNative.ScrollView, {
View compiled
Module.../../../../../../../../../../../Projects/react-native/expo-react-navigation-web-example/node_modules/react-native-gesture-handler/GestureHandler.js
http://192.168.50.5:19006/static/js/bundle.js:83766:30
__webpack_require__
expo-react-navigation-web-example/webpack/bootstrap:724
```

I'm looking to get react-navigation working with expo web.

You can play around with switching expo versions with:
`npm run install expo:next`
`npm run install expo:latest-web`
etc.