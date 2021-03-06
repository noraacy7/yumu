# [yumu](https://github.com/yumu-webpack/yumu)
[![NPM version](https://img.shields.io/npm/v/yumu.svg?style=flat)](https://npmjs.org/package/yumu)
[![npm](https://img.shields.io/npm/dt/yumu.svg)](https://npmjs.org/package/yumu)
[![GitHub stars](https://img.shields.io/github/stars/yumu-webpack/yumu.svg?style=social&label=Star)](https://github.com/yumu-webpack/yumu)
[![GitHub forks](https://img.shields.io/github/forks/yumu-webpack/yumu.svg?style=social&label=Fork)](https://github.com/yumu-webpack/yumu)

yumu webpack and react solution

----

## Feature

- Generate a [webpack](https://github.com/webpack/webpack) based boilerplate.
- Run a local server for web developer, support proxy and HMR.
- Easy to use and customize third-party UI components.
- Support customized webpack.config.js.
- Support `buildvars` to automatically output bundles with different varible combinations.


## Install

- Install yumu

```bash
$ npm i yumu -g
```


## Usage

- Generate a boilerplate.

```bash
$ yumu init
$ yumu init -t (you will choose your template like single page application or multiple page application)
```

- Install the dependencies.

```bash
$ cd xx(the project path)
$ yumu install
```

- Start a local dev server.

```bash
$ yumu server
```
> It will listen to the port 8080

- Build project.

```bash
$ yumu build 
```
