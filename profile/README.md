<img align="left" style="max-width: 100%" src="https://raw.githubusercontent.com/chef-js/core/main/chef.svg" width="170" />

- **static-files-server** designed for **single-page-applications**
- written in **typescript**, usable as a **command-line-tool** (or **runtime library**)
- with **many tests** and **continuous-integration**
- optional **404** fallback to **index.html** with a **200** status code (spa)
- optional **web-sockets** micro-service manager on **same port**

# Express
<a href="https://badge.fury.io/js/chef-express"><img src="https://badge.fury.io/js/chef-express.svg" alt="npm package version" /></a> <a href="https://circleci.com/gh/chef-js/express"><img src="https://circleci.com/gh/chef-js/express.svg?style=shield" alt="tests status" /></a>

The most basic flavor of the core library - serve folder. port defaults to 3000

```
npx chef-express folder
```

see [chef-express](https://github.com/chef-js/express) for more information about command line parameters

# Socket
<a href="https://badge.fury.io/js/chef-socket"><img src="https://badge.fury.io/js/chef-socket.svg" alt="npm package version" /></a> <a href="https://circleci.com/gh/chef-js/socket"><img src="https://circleci.com/gh/chef-js/socket.svg?style=shield" alt="tests status" /></a>

On top of the base adds socket.io for websockets functionality on the same port.

```
npx chef-socket folder --plugin path/to/plugin.js
```

see [chef-socket](https://github.com/chef-js/socket) to find out more

## demo (with chat plugin)

https://chef-socket.pietal.dev/
