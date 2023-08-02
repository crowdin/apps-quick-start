<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://support.crowdin.com/assets/logos/symbol/png/crowdin-symbol-cWhite.png">
    <source media="(prefers-color-scheme: light)" srcset="https://support.crowdin.com/assets/logos/symbol/png/crowdin-symbol-cDark.png">
    <img width="150" height="150" width=""src="[https://support.crowdin.com/assets/logos/symbol/png/crowdin-symbol-cDark.png](https://crowdin.com)">
  </picture>
</p>

# Getting Started with Crowdin Apps

Join the growing localization management platform! Build apps for all the teams already using Crowdin or Crowdin Enterprise to customize and extend localization experience. By creating Crowdin apps, developers can integrate existing services with Crowdin, add new features, upload and manage content.

<div align="center">

[**`Home`**](https://crowdin.com) &nbsp;|&nbsp;
[**`Quick Start`**](https://developer.crowdin.com/crowdin-apps-quick-start) &nbsp;|&nbsp;
[**`Developers Portal`**](https://developers.crowdin.com/)

</div>

## Running Locally

Make sure you have [Node.js](http://nodejs.org/) installed.

```sh
$ git clone https://github.com/crowdin/apps-quick-start.git # or clone your own fork
$ cd apps-quick-start
$ npm install
$ npm start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

Make sure you have [Heroku CLI](https://cli.heroku.com/) installed.

```
$ heroku create
$ git push heroku main
$ heroku open
```

or

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Documentation

For more information about using Node.js on Heroku, see these Dev Center articles:

- [Crowdin Developers Portal](https://developers.crowdin.com/)
- [Quick Start](https://developer.crowdin.com/crowdin-apps-quick-start)
- [Getting Started on Heroku with Node.js](https://devcenter.heroku.com/articles/getting-started-with-nodejs)
- [Node.js on Heroku](https://devcenter.heroku.com/categories/nodejs)
- [Best Practices for Node.js Development](https://devcenter.heroku.com/articles/node-best-practices)
