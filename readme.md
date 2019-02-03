# Dev Notes

Following [Facebook official guide](https://facebook.github.io/react-native/docs/getting-started.html).

- Setup dev environment

**Caution**

Before installing watchman, this will require `python`, which is in fact python3. When you install `mongodb`, brew will install python@2. Please notice this and will potentially let you re-install python3 in homebrew. This will install latest Python like 3.7. If you need 3.6, you have to consider using `pyenv`. Still not sure how pyenv interacts with homebrew's package.

```sh
brew install watchman
npm install -g react-native-cli
```