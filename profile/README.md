<img align="left" style="max-width: 100%" src="https://raw.githubusercontent.com/chef-js/core/main/chef.svg" width="170" />

- on the **same port**:
- **static-files-server** designed for **single-page-applications**
- **404**'s fallback to **index.html** with a **200** status code
- written in **typescript**, usable as a **command-line-interface** (or **runtime libraries**)
- with **many tests** and **continuous-integration**
- and [optional] **web-sockets** micro-service manager

# Express
<a href="https://badge.fury.io/js/chef-express"><img src="https://badge.fury.io/js/chef-express.svg" alt="npm package version" /></a> <a href="https://circleci.com/gh/chef-js/express"><img src="https://circleci.com/gh/chef-js/express.svg?style=shield" alt="tests status" /></a>

The most basic flavor of the core library - doesn't have websockets functionality

```
npx chef-express folder
```

see [chef-express](https://github.com/chef-js/express) for more information about command line parameters

# Socket
<a href="https://badge.fury.io/js/chef-socket"><img src="https://badge.fury.io/js/chef-socket.svg" alt="npm package version" /></a> <a href="https://circleci.com/gh/chef-js/socket"><img src="https://circleci.com/gh/chef-js/socket.svg?style=shield" alt="tests status" /></a>

On top of the Express adds socket.io for websockets functionality (at the same port as the http server)

```
npx chef-socket folder --plugin path/to/plugin.js
```

demo (with chat plugin)

https://chef-js-socket.herokuapp.com/

see [chef-socket](https://github.com/chef-js/socket) to find out more

# Core
<a href="https://badge.fury.io/js/chef-core"><img src="https://badge.fury.io/js/chef-core.svg" alt="npm package version" /></a> <a href="https://circleci.com/gh/chef-js/core"><img src="https://circleci.com/gh/chef-js/core.svg?style=shield" alt="tests status" /></a>

A base library for above 3 having the plugin handling and static-files serving functionalities inside

see [chef-core](https://github.com/chef-js/core) to find out more
