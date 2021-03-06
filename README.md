<p align="center">
  <img src="https://github.com/metrue/YoYo/raw/master/YoYo.png"/>
</p>

A dead simple, dead lightweight comment engine alternative to Disqus.

---

<p align="center">
  <img src="https://circleci.com/gh/metrue/YoYo.svg?&style=shield&circle-token=964ea66301703e4612ad72ec839ba2d4fa2f98b4"/>
  <img src="https://codecov.io/github/metrue/YoYo/coverage.svg?branch=master"/>
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg"/>
</p>
<p align="center">
  <img src="https://github.com/metrue/YoYo/raw/master/screenshot.png" width='200' height='352' style="border: solid lightgrey 1px;"/>
  <img src="https://github.com/metrue/YoYo/raw/master/screenshot-zh.png" width='200' height='352' style="border: solid lightgrey 1px;"/>
</p>

### Usage

Place the following code where you'd like YoYo to load:

```
<div id="YoYo"></div>
<script src="https://yoyo.minghe.me/dist/v0.1/index.js"></script>
```

### Installation

* clone YoYo

```
$ git clone https://github.com/metrue/YoYo
```

* start YoYo API Server

YoYo server is using [MongoDB](https://docs.mongodb.com/manual/) as database server, so you need to start your MongoDB server install first.

```
$ mongod
$ cd YoYo/backend && npm run start
```

* start YoYo client

```
$ cd YoYo/client && npm run develop
```

then YoYo is running on https://localhost:8080


### Showcases

* [https://minghe.me](https://minghe.me)
* [https://asmalltalk.com](https://asmalltalk.com)

### LICENSE

MIT
