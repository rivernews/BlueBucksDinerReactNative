# Blue Bucks Diner

This app implements [the design project named after the same title](https://shaungc.com/portfolio/4), which aims to improve the dining experience on campus of University of Michigan. The backend [resides in a separated repository](https://github.com/rivernews/bb-rest-api). This is a personal project along with SI 691: Independent Study.

**Tech Stack**

- Front End: React Native
- Backend: Node.js + MongoDB + Nginx
- DevOps: Docker + Terraform + AWS ECS

# Getting Started

- To run the app in a iOS simulator, run `react-native run-ios`.

# Dev Notes

**TODO:** move this dev notes (diary) to a dedicated place. Only public-facing content here.

Following [Facebook official guide](https://facebook.github.io/react-native/docs/getting-started.html).

- Setup dev environment

**Caution**

Before installing watchman, this will require `python`, which is in fact python3. When you install `mongodb`, brew will install python@2. Please notice this and will potentially let you re-install python3 in homebrew. This will install latest Python like 3.7. If you need 3.6, you have to consider using `pyenv`. Still not sure how pyenv interacts with homebrew's package.

```sh
brew install watchman
npm install -g react-native-cli
```

- Requesting API to the backend: [Networking](https://facebook.github.io/react-native/docs/network).