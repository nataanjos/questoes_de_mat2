
React Native brings [**React**'s][r] declarative UI framework to iOS and Android. With React Native, you use native UI controls and have full access to the native platform.

- **Declarative.** React makes it painless to create interactive UIs. Declarative views make your code more predictable and easier to debug.
- **Component-Based.** Build encapsulated components that manage their state, then compose them to make complex UIs.
- **Developer Velocity.** See local changes in seconds. Changes to JavaScript code can be live reloaded without rebuilding the native app.
- **Portability.** Reuse code across iOS, Android, and [other platforms][p].

React Native is developed and supported by many companies and individual core contributors. Find out more in our [ecosystem overview][e].

[r]: https://reactjs.org/
[p]: https://reactnative.dev/docs/out-of-tree-platforms
[e]: https://github.com/facebook/react-native/blob/master/ECOSYSTEM.md

## Contents

- [Contents](#contents)
- [📋 Requirements](#-requirements)
- [🎉 Building your first React Native app](#-building-your-first-react-native-app)
- [📖 Documentation](#-documentation)
- [🚀 Upgrading](#-upgrading)
- [👏 How to Contribute](#-how-to-contribute)
  - [Code of Conduct](#code-of-conduct)
  - [Contributing Guide](#contributing-guide)
  - [Open Source Roadmap](#open-source-roadmap)
  - [Good First Issues](#good-first-issues)
  - [Discussions](#discussions)
- [📄 License](#-license)


## 📋 Requirements

React Native apps may target iOS 10.0 and Android 4.1 (API 16) or newer. You may use Windows, macOS, or Linux as your development operating system, though building and running iOS apps is limited to macOS. Tools like [Expo](https://expo.io) can be used to work around this.

## 🎉 Building your first React Native app

Follow the [Getting Started guide](https://reactnative.dev/docs/getting-started.html). The recommended way to install React Native depends on your project. Here you can find short guides for the most common scenarios:

- [Trying out React Native][hello-world]
- [Creating a New Application][new-app]
- [Adding React Native to an Existing Application][existing]

[hello-world]: https://snack.expo.io/@hramos/hello,-world!
[new-app]: https://reactnative.dev/docs/getting-started.html
[existing]: https://reactnative.dev/docs/integration-with-existing-apps.html

## 📖 Documentation

The full documentation for React Native can be found on our [website][docs].

The React Native documentation discusses components, APIs, and topics that are specific to React Native. For further documentation on the React API that is shared between React Native and React DOM, refer to the [React documentation][r-docs].

The source for the React Native documentation and website is hosted on a separate repo, [**@facebook/react-native-website**][repo-website].

[docs]: https://reactnative.dev/docs/getting-started.html
[r-docs]: https://reactjs.org/docs/getting-started.html
[repo-website]: https://github.com/facebook/react-native-website

## 🚀 Upgrading

Upgrading to new versions of React Native may give you access to more APIs, views, developer tools, and other goodies. See the [Upgrading Guide][u] for instructions.

React Native releases are discussed in the React Native Community, [**@react-native-community/react-native-releases**][repo-releases].

[u]: https://reactnative.dev/docs/upgrading
[repo-releases]: https://github.com/react-native-community/react-native-releases

## 👏 How to Contribute

The main purpose of this repository is to continue evolving React Native core. We want to make contributing to this project as easy and transparent as possible, and we are grateful to the community for contributing bug fixes and improvements. Read below to learn how you can take part in improving React Native.

### [Code of Conduct][code]

Facebook has adopted a Code of Conduct that we expect project participants to adhere to.
Please read the [full text][code] so that you can understand what actions will and will not be tolerated.

[code]: https://code.fb.com/codeofconduct/

### [Contributing Guide][contribute]

Read our [**Contributing Guide**][contribute] to learn about our development process, how to propose bugfixes and improvements, and how to build and test your changes to React Native.

[contribute]: https://reactnative.dev/docs/contributing

### [Open Source Roadmap][roadmap]

You can learn more about our vision for React Native in the [**Roadmap**][roadmap].

[roadmap]: https://github.com/facebook/react-native/wiki/Roadmap

### Good First Issues

We have a list of [good first issues][gfi] that contain bugs which have a relatively limited scope. This is a great place to get started, gain experience, and get familiar with our contribution process.

[gfi]: https://github.com/facebook/react-native/labels/good%20first%20issue

### Discussions

Larger discussions and proposals are discussed in [**@react-native-community/discussions-and-proposals**][repo-meta].

[repo-meta]: https://github.com/react-native-community/discussions-and-proposals

## 📄 License

React Native is MIT licensed, as found in the [LICENSE][l] file.

React Native documentation is Creative Commons, as found in the [LICENSE-docs][ld] file.

[l]: https://github.com/facebook/react-native/blob/master/LICENSE
[ld]: https://github.com/facebook/react-native/blob/master/LICENSE-docs

$\ce{Hg^2+ ->[I-] HgI2 ->[I-] [Hg^{II}I4]^2-}$


# Metro

[![CircleCI Build Status](https://circleci.com/gh/facebook/metro.svg?style=shield)](https://circleci.com/gh/facebook/metro)
[![npm version](https://badge.fury.io/js/metro.svg)](http://badge.fury.io/js/metro)
[![codecov](https://codecov.io/gh/facebook/metro/branch/master/graph/badge.svg)](https://codecov.io/gh/facebook/metro)

🚇 The JavaScript bundler for React Native.

- **🚅 Fast**: We aim for sub-second reload cycles, fast startup and quick bundling speeds.
- **⚖️ Scalable**: Works with thousands of modules in a single application.
- **⚛️ Integrated**: Supports every React Native project out of the box.

This project was previously part of the [react-native](https://github.com/facebook/react-native) repository. In this smaller repository it is easier for the team working on Metro to respond to both issues and pull requests. See [react-native#13976](https://github.com/facebook/react-native/issues/13976) for the initial announcement.

## Installation & Documentation

See [the Metro website](https://facebook.github.io/metro/) for documentation.

## License

Metro is MIT licensed, as found in the LICENSE file.

![codecov](0.jpg)