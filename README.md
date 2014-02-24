## Installation

### Install [homesick](https://github.com/technicalpickles/homesick) and clone dotfiles

```sh
$ gem install homesick
$ homesick clone nnasaki/dotfiles
$ homesick symlink nnasaki/dotfiles
```

#### TIPS:Proxy
If you need proxy, create file `~/.profile` and settings below.
Then run source `~/.profile`.

```sh
$http_proxy=http://yourproxyhost:port/
$https_proxy=http://yourproxyhost:port/
export no_proxy=localhost,127.0.0.0/8
```

If you `sudo gem install …`,  exec `sudo visudo` and add below line.

```sh
Defaults        env_keep += "http_proxy https_proxy no_proxy"
```

### Install [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)

```sh
$ git clone git://github.com/robbyrussell/oh-my-zsh.git ‾/.oh-my-zsh
```

### Install [Homebrew](http://brew.sh/)

```sh
$ ruby -e "$(curl -fsSL https://raw.github.com/mxcl/homebrew/go/install)"
```
