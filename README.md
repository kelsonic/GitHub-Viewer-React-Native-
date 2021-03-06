# GitHub Notetaker

This app is built with React Native.

GitHub Viewer allows you to search for GitHub users, browse their public information and repositories, as well as leave notes for each user.

### View the app live

[![GitHub Notetaker](readme-image.png)](https://youtu.be/SnQCfvzQh6U)

## Installation (MAC OS X)

### Run the App

You will need Brew, NodeJS and Xcode.

Then, install the React Native command line tools:

```
npm install -g react-native-cli
```

Install Watchman and Flow:
```
brew install watchman

brew install flow
```

To run the application, navigate to its directory and run the command:

```
react-native run-ios
```

#### Installation Notes

You might need to also to take care of Node dependencies using

```
npm install
npm start
```

If you have trouble with the version of Node, you can install a newer version using:

```
npm install -g n
n v4.1.2

# Verify the Node version
node -v
```

## Contributing

Do you see any errors or do you want to extend this app? Make a pull-request! They are very welcome.

## Credits

* [kelsonic](https://github.com/kelsonic)

## License

MIT License. View the full license in [LICENSE](LICENSE).