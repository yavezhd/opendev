# async-file-dl

[![Build Status](https://travis-ci.org/OpenByteDev/async-file-dl.svg?branch=master)](https://travis-ci.org/OpenByteDev/async-file-dl)
[![npm version](https://badge.fury.io/js/async-file-dl.svg)](https://www.npmjs.com/package/async-file-dl)
[![Maintainability](https://api.codeclimate.com/v1/badges/79490a06fbe1b1ae1dfb/maintainability)](https://codeclimate.com/github/OpenByteDev/async-file-dl/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/79490a06fbe1b1ae1dfb/test_coverage)](https://codeclimate.com/github/OpenByteDev/async-file-dl/test_coverage)
[![Dependency Status](https://david-dm.org/OpenByteDev/async-file-dl/status.svg)](https://david-dm.org/OpenByteDev/async-file-dl)
[![DevDependency Status](https://david-dm.org/OpenByteDev/async-file-dl/dev-status.svg)](https://david-dm.org/OpenByteDev/async-file-dl?type=dev)
[![License](https://img.shields.io/github/license/mashape/apistatus.svg)](https://opensource.org/licenses/MIT)
[![Doge](https://img.shields.io/badge/doge-wow-yellow.svg)]()


A simple asynchronous file downloader based on axios.

### Installation
```bash
$ npm install async-file-dl
```

### Usage
```js
const { download } = require('async-file-dl');

download('http://example.com/', '.', 'example.html')
  .then(file => console.log('download successful')
  .catch(console.error);
```

### API
The API generated with [TypeDoc](http://typedoc.org/) can be found [here](https://openbytedev.github.io/async-file-dl/).
