# VuePress Plugin Matomo Analytics

This project add [Matomo](https://matomo.org/) support for [vuepress](https://vuepress.vuejs.org/).

FYI Matomo is a powerful web analytics platform that gives you and your business 100% data ownership and user privacy protection.

> This plugin is based on the official VuePress plugin  [@vuepress/plugin-google-analytics](https://github.com/vuejs/vuepress/tree/master/packages/%40vuepress/plugin-google-analytics) - [npm](https://www.npmjs.com/package/@vuepress/plugin-google-analytics).


## Install

```sh
$ 

# or

$ 
```

## Usage

Add `vuepress-plugin-matomo` in your site or theme config file.

> See [official docs](https://vuepress.vuejs.org/plugin/using-a-plugin.html)


```js
// .vuepress/config.js
// or
// .vuepress/theme/index.js

module.exports = {
  plugins: [
    ['matomo', {trackerUrl: 'XXX', siteId: 'YYY'}]
  ]
}
```

## License

[**GNU General Public License version 3**](https://opensource.org/licenses/GPL-3.0)
