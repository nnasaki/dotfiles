## Installation

### Install [homesick](https://github.com/technicalpickles/homesick) and clone dotfiles

```sh
$ gem install homesick
$ homesick clone nnasaki/dotfiles
$ homesick symlink nnasaki/dotfiles
```

If you need proxy, create file `~/.profile` and settings below.
Then run source `~/.profile`.

```sh
$http_proxy=http://yourproxyhost:port/
$https_proxy=http://yourproxyhost:port/
export no_proxy=localhost,127.0.0.0/8
```

### Install [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)

```sh
$ git clone git://github.com/robbyrussell/oh-my-zsh.git ‾/.oh-my-zsh
```

### Install [Homebrew](http://brew.sh/)

```sh
$ ruby -e "$(curl -fsSL https://raw.github.com/mxcl/homebrew/go/install)"
```
