# Halogen Template

### Quick Start
```sh
git clone https://github.com/harryprayiv/purs-nix-halogen-template.git halogen-project
cd halogen-project/
nix develop
purs-nix compile
vite --open
```

### Introduction

This is a template for starting a fresh project with the [Halogen](https://github.com/purescript-halogen/purescript-halogen) library for writing declarative, type-safe user interfaces.

You can learn more about Halogen with these resources:

- The [Halogen documentation](https://github.com/purescript-halogen/purescript-halogen/tree/master/docs), which includes a quick start guide and a concepts reference.
- The [Learn Halogen](https://github.com/jordanmartinez/learn-halogen) learning repository.
- The [Real World Halogen](https://github.com/thomashoneyman/purescript-halogen-realworld) application and guide. Note that the published article is written for the older halogen v4, but the code and comments cover the current halogen v5.
- The [API documentation](https://pursuit.purescript.org/packages/purescript-halogen) on Pursuit

You can chat with other Halogen users on the [PureScript Discourse](https://discourse.purescript.org), or join the [Functional Programming Slack](https://functionalprogramming.slack.com) ([invite link](https://fpchat-invite.herokuapp.com/)) in the `#purescript` and `#purescript-beginners` channels.

If you notice any problems with the below setup instructions, or have suggestions on how to make the new-user experience any smoother, please create an issue or pull-request.

Compatible with PureScript compiler 15.x

### Initial Setup

**Prerequisites:** This template assumes you already have nix installed.

First, clone the repository and step into it:

```sh
git clone https://github.com/harryprayiv/purs-nix-halogen-template.git halogen-project
cd halogen-project
nix develop
```

Then, nix will install the PureScript compiler, the [Spago](https://github.com/purescript/spago) package manager and build tool, and the [Vite](https://github.com/vitejs/vite) bundler.


### Building

You can now build the PureScript source code with:

```sh
# An alias for `spago build`
purs-nix compile
```

### Launching the App

You can launch your app in the browser with:

```sh
vite --open
```

### Development Cycle

If you're using an [editor](https://github.com/purescript/documentation/blob/master/ecosystem/Editor-and-tool-support.md#editors) that supports [`purs ide`](https://github.com/purescript/purescript/tree/master/psc-ide) or are running [`pscid`](https://github.com/kRITZCREEK/pscid), you simply need to run the command ``purs-watch``. Any save to a file will trigger an incremental recompilation, rebundle, and web page refresh, so you can immediately see your changes.
