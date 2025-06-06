# chef-js

## start cooking!

- **chef-*** is a **static-files-server**
- written in **typescript**
- usable as a **command-line-tool** (or **runtime library**)
- with **many tests** and **continuous-integration**
- optional **404** fallback to **index.html** with a **200** status code (spa)
- optional **cache**
- optional **web-sockets** micro-service manager on **same port**

## Express

[<img src="https://img.shields.io/npm/v/chef-express?style=for-the-badge&color=success" alt="npm version" />](https://www.npmjs.com/package/chef-express)
[<img src="https://img.shields.io/circleci/build/github/chef-js/express/main?style=for-the-badge" alt="build status" />](https://app.circleci.com/pipelines/github/chef-js/express)

The most basic flavor of the core library - serve folder. port defaults to 3000

```
npx chef-express folder
```

see [chef-express](https://github.com/chef-js/express) for more information about command line parameters

## Socket

[<img src="https://img.shields.io/npm/v/chef-socket?style=for-the-badge&color=success" alt="npm version" />](https://www.npmjs.com/package/chef-socket)
[<img src="https://img.shields.io/circleci/build/github/chef-js/socket/main?style=for-the-badge" alt="build status" />](https://app.circleci.com/pipelines/github/chef-js/socket)

On top of the base adds socket.io for websockets functionality on the same port.

```
npx chef-socket folder [--plugin node_modules/chef-socket/chat.js]
```

see [chef-socket](https://github.com/chef-js/socket) to find out more

### demo (with chat plugin)

https://chef-socket.pietal.dev/
