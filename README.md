# 🌳 SpanTree

[![](https://img.shields.io/github/stars/tavyandy97/span-tree?color=red&style=for-the-badge)](https://github.com/tavyandy97/span-tree)&nbsp;
[![](https://img.shields.io/chrome-web-store/users/gcjikeldobhnaglcoaejmdlmbienoocg?style=for-the-badge)](https://chrome.google.com/webstore/detail/spantree-gitlab-tree/gcjikeldobhnaglcoaejmdlmbienoocg)&nbsp;
[![](https://img.shields.io/chrome-web-store/v/gcjikeldobhnaglcoaejmdlmbienoocg?style=for-the-badge)](https://chrome.google.com/webstore/detail/spantree-gitlab-tree/gcjikeldobhnaglcoaejmdlmbienoocg)&nbsp;
[![](https://img.shields.io/amo/v/spantree-gitlab-tree?style=for-the-badge)](https://addons.mozilla.org/en-GB/firefox/addon/spantree-gitlab-tree/)&nbsp;
[![](https://img.shields.io/badge/Made%20With-React-%2340D8FC?color=dodgerblue&logo=react&style=for-the-badge)](https://reactjs.org/)

![](docs//banner.png)

## 📖 About

Browser extension that makes navigating a GitLab repository feel like a breeze by providing a familiar tree structure.<br>
- [Chrome Extension](https://chrome.google.com/webstore/detail/spantree-gitlab-tree/gcjikeldobhnaglcoaejmdlmbienoocg)<br>
- [Firefox Add-on](https://addons.mozilla.org/en-GB/firefox/addon/spantree-gitlab-tree)<br>

![](docs/demo.gif)

## ✨ Stargazers

[![Stargazers repo roster for @tavyandy97/span-tree](https://reporoster.com/stars/tavyandy97/span-tree)](https://github.com/tavyandy97/span-tree/stargazers)

## 💻 Development Setup

Pre-Requisites:

1. Install Node.js (v10.17.0)

2. Install gulp-cli

   ```
   $ npm install -g gulp-cli
   ```

Steps:

1. Clone the repository to your local system

2. Install all the dependencies

   ```bash
   $ npm install
   ```

3. Now to start the server which shall compile the extension in real time

   ```
   $ gulp watch
   ```

   (You'll observe a build folder being formed inside the project folder)

4. Load the chrome extension from the build folder. ( first enable developer mode inside Chrome)

   (For reference follow: https://thoughtbot.com/blog/how-to-make-a-chrome-extension)

5. 如果你想获取打包之后的产物
    ```bash
    npm run pack
    ```
6. 如果不能访问谷歌应用商店，可以直接使用项目目录中的 `span-tree-gitlab`

## 💳 Credits

SpanTree uses the following open-source packages:

- [react](https://github.com/facebook/react)
- [redux](https://github.com/reduxjs/redux)
- [webext-redux](https://github.com/tshaddix/webext-redux)
- [file-icons](https://github.com/file-icons/atom)
- [dark-gitlab](https://gitlab.com/vednoc/dark-gitlab)
- [axios](https://github.com/axios/axios)
- [immer](https://github.com/immerjs/immer)
- [fzy.js](https://github.com/jhawthorn/fzy.js)
