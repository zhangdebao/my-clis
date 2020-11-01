# my-clis

[![NPM Downloads][downloads-image]][downloads-url]
[![NPM Version][version-image]][version-url]
[![License][license-image]][license-url]
[![Dependency Status][dependency-image]][dependency-url]
[![devDependency Status][devdependency-image]][devdependency-url]
[![Code Style][style-image]][style-url]

> static web app workflow

## Installation

```shell
$ npm install my-clis

# or yarn
$ yarn add my-clis
```

## Usage

<!-- TODO: Introduction of API use -->

```javascript
const myClis = require('my-clis')
const result = myClis('zce')
// result => 'zce@zce.me'
```

## API

<!-- TODO: Introduction of API -->

### myClis(name[, options])

#### name

- Type: `string`
- Details: name string

#### options

##### host

- Type: `string`
- Details: host string
- Default: `'zce.me'`

## Contributing

1. **Fork** it on GitHub!
2. **Clone** the fork to your own machine.
3. **Checkout** your feature branch: `git checkout -b my-awesome-feature`
4. **Commit** your changes to your own branch: `git commit -am 'Add some feature'`
5. **Push** your work back up to your fork: `git push -u origin my-awesome-feature`
6. Submit a **Pull Request** so that we can review your changes.

> **NOTE**: Be sure to merge the latest from "upstream" before making a pull request!

## License

[MIT](LICENSE) &copy; zhangdebao <1127701327@qq.com>



[downloads-image]: https://img.shields.io/npm/dm/my-clis.svg
[downloads-url]: https://npmjs.org/package/my-clis
[version-image]: https://img.shields.io/npm/v/my-clis.svg
[version-url]: https://npmjs.org/package/my-clis
[license-image]: https://img.shields.io/github/license/my-clis/my-clis.svg
[license-url]: https://github.com/my-clis/my-clis/blob/master/LICENSE
[dependency-image]: https://img.shields.io/david/my-clis/my-clis.svg
[dependency-url]: https://david-dm.org/my-clis/my-clis
[devdependency-image]: https://img.shields.io/david/dev/my-clis/my-clis.svg
[devdependency-url]: https://david-dm.org/my-clis/my-clis?type=dev
[style-image]: https://img.shields.io/badge/code_style-standard-brightgreen.svg
[style-url]: https://standardjs.com
