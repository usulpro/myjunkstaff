
[<img src="doc/logo-small.png" align="left" class="logo" width="280"/>](https://github.com/sm-react/react-theming) 

<div align="right" style="margin: 8px">
<sub>Created with ❤︎ to <b>React</b> and <b>React Storybook</b> by <a href="https://twitter.com/UsulPro">UsulPro</a>.</sub>
</div>

**React-Theming** provides a set of tools for developing themable React apps with **React-Storybook** under the hood. This project includes three main parts:

 :small_blue_diamond: | :small_blue_diamond:  |  :small_blue_diamond:  | :small_blue_diamond:  |  :small_blue_diamond:  
------ | ----- | ------ | ---- | ----
[Addon for Storybook](https://github.com/sm-react/storybook-addon-material-ui) | The core of React-Theming | [![GitHub stars](https://img.shields.io/github/stars/sm-react/storybook-addon-material-ui.svg?style=social&label=Star)](https://github.com/sm-react/storybook-addon-material-ui) | [![Live demo](https://img.shields.io/badge/Live%20Demo-%20Storybook-brightgreen.svg)](https://sm-react.github.io/storybook-addon-material-ui) | [![npm version](https://badge.fury.io/js/storybook-addon-material-ui.svg)](https://badge.fury.io/js/storybook-addon-material-ui) 
[React Theme Provider](https://github.com/sm-react/react-theme-provider) | A generic theme provider and (very) simple CSS styler |  [![GitHub stars](https://img.shields.io/github/stars/sm-react/react-theme-provider.svg?style=social&label=Star)](https://github.com/sm-react/react-theme-provider) | [![Live demo](https://img.shields.io/badge/Live%20Demo-%20Storybook-brightgreen.svg)](https://sm-react.github.io/react-theme-provider) | [![npm version](https://badge.fury.io/js/react-theme-provider.svg)](https://badge.fury.io/js/react-theme-provider)  
[The Boilerplate Project](https://github.com/UsulPro/myjunkstaff/blob/master/docs/readme.md#storybook-boilerplate-project) | Starting point for apps development | [![GitHub stars](https://img.shields.io/github/stars/sm-react/react-theming.svg?style=social&label=Star)](https://github.com/sm-react/react-theming) | [![Live demo](https://img.shields.io/badge/Live%20Demo-%20Storybook-brightgreen.svg)](https://sm-react.github.io/react-theming) | [![GitHub version](https://badge.fury.io/gh/sm-react%2Freact-theming.svg)](https://badge.fury.io/gh/sm-react%2Freact-theming)

---

## Storybook Boilerplate Project

[![GitHub version](https://badge.fury.io/gh/sm-react%2Freact-theming.svg)](https://badge.fury.io/gh/sm-react%2Freact-theming)


At the heart of this project the desire to collect the best practices of application development via [React-Storybook](https://github.com/storybooks/react-storybook) environment.

It contains the *fully-charged* setup of the Storybook with **pre-installed plugins**, configuration, quick examples, and tips. Inspired by [Create React App](https://github.com/facebookincubator/create-react-app) and [React CDK](https://github.com/kadirahq/react-cdk).

### Features

- React Storybook Addons:

 - [<img src="doc/msm.png" alt="Milestone" width="22">](#roadmap) [React Storybook Info Addon](https://github.com/storybooks/react-storybook-addon-info) - *show additional <b>information</b> for your stories*

 - [<img src="doc/msm.png" alt="Milestone" width="22">](#roadmap) [Storybook Addon Notes](https://github.com/storybooks/storybook-addon-notes) - *allows you to write <b>notes</b> for your stories*

 - [Storybook Addon Actions](https://github.com/storybooks/storybook-addon-actions) (included by default) - *the <b>Action Logger</b> addon can be used to display data received by event handlers*

 - [<img src="doc/msm.png" alt="Milestone" width="22">](#roadmap) [Storybook Addon Knobs ](https://github.com/storybooks/storybook-addon-knobs) - *allows you to <b>edit</b> React props dynamically*

 - [Storybook Addon Material-UI](https://github.com/sm-react/storybook-addon-material-ui) - *provides live <b>theme</b> creating environment to React Storybook*

- Testing:

 - [<img src="doc/msm.png" alt="Milestone" width="22">](#roadmap) [StoryShots](https://github.com/storybooks/storyshots) - *provides [Snapshot Testing](https://facebook.github.io/jest/blog/2016/07/27/jest-14.html) for React Storybook*
 
 - [Mocha](https://github.com/mochajs/mocha) and [Enzyme](https://github.com/airbnb/enzyme)

- React ecosystem:

 - [Material-UI](http://www.material-ui.com/#/) - *via [Storybook Addon Material-UI](https://github.com/sm-react/storybook-addon-material-ui)*
 
 - [React Theme Provider](https://github.com/sm-react/react-theme-provider)

- Workflow *(via NPM scripts command)*:

 - [<img src="doc/msm.png" alt="Milestone" width="22">](#roadmap) Build your App with [Webpack](https://github.com/webpack/webpack) and [Babel](https://github.com/babel/babel)
 
 - Publish transpiled code into NPM
 
 - Run tests

 - [ESLint](https://github.com/eslint/eslint) with the [Airbnb style guide](https://github.com/airbnb/javascript)
 
 - Deploy your storybook to GitHub Pages
 

### Roadmap

[<img src="doc/msm.png" alt="Milestone" width="22">](#roadmap) Add [Styled Components](https://github.com/styled-components/styled-components) support

[<img src="doc/msm.png" alt="Milestone" width="22">](#roadmap) Deploy your App to GitHub Pages

[<img src="doc/msm.png" alt="Milestone" width="22">](#roadmap) Suggest your [feature](/../../issues) wich you'd like to see here!

[<img src="doc/msm.png" alt="Milestone" width="22">](#roadmap) [storybook-addon-comments](https://github.com/storybooks/storybook-addon-comments) - *allows you to add comments for your stories*

[<img src="doc/msm.png" alt="Milestone" width="22">](#roadmap) [storybook-addon-options](https://github.com/storybooks/storybook-addon-options) - *set configure the Storybook UI*

[<img src="doc/msm.png" alt="Milestone" width="22">](#roadmap) Short tutorial for using this tools

### Quick start

```shell
git clone https://github.com/sm-react/react-theming.git
cd react-theming
npm i
npm start
start http://localhost:9001/
```

### Contribute

We'll appreciate any help, ideas, issues and feedback!

