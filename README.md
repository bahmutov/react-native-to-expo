# react-native-to-expo
> Adding Expo to an existing react-native project

Created a simple React Native example following this [tutorial](https://reactnative.dev/docs/tutorial).

```
$ npm i -D react react-native
+ react@17.02
+ react-native@0.64.2
```

Then added Expo using [the doc](https://docs.expo.io/guides/running-in-the-browser/)

```
$ npm i -D expo react-native-web react-dom
+ react-dom@17.0.2
+ expo@41.0.1
+ react-native-web@0.17.0
```

Remove the `main` and add a shortcut to run Expo

```json
{
  "scripts": {
    "start": "react-native start",
    "web": "expo start --web"
  },
  "devDependencies": {
    "expo": "^41.0.1",
    "react": "^17.0.2",
    "react-dom": "^17.0.2",
    "react-native": "^0.64.2",
    "react-native-web": "^0.17.0"
  }
}
```

Execute `npm run web` and the app should run at `localhost:19006`
