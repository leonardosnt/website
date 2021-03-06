### macOS

#### Homebrew

You can install Yarn through the [Homebrew package manager](http://brew.sh/).
This will also install Node.js if it is not already installed.

```sh
brew install yarn
```

If you use [nvm](https://github.com/creationix/nvm) or similar, you should exclude installing Node.js so that nvm's version of Node.js is used.

```sh
brew install yarn --without-node
```

#### MacPorts

You can install Yarn through [MacPorts](https://www.macports.org/).
This will also install Node.js if it is not already installed.

```sh
sudo port install yarn
```

#### Path Setup

<!-- prettier-ignore -->
{% include_relative _installations/unix_path_setup.md %}

#### Upgrade Yarn

Yarn will warn you if a new version is available.
To upgrade Yarn, you can do so with Homebrew.

```sh
brew upgrade yarn
```
