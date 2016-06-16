# vimenv
vimenv is like rbenv to vim.

# init
```
$ git clone https://github.com/longicorn/vimenv.git ~/.vimenv
```

```
export PATH=~/.vimenv/bin:$PATH
export PATH=~/.vimenv/libexec/bin:$PATH
```

```
$ vimenv init
```

# update
update source code
```
$ vimenv update
```

# install
print install versions list
```
$ vimenv list
```

install & run

vim
```
# Linux
$ vimenv install vim v7.4b.022 --with-features=huge --enable-cscope --enable-fontset

# Mac
$ CC=gcc-4.9 vimenv install vim v7.4b.022 --with-features=huge  --enable-cscope --enable-fontset

$ vimenv global vim v7.4b.022
$ vim
```

neovim
```
# Linux & Mac
$ vimenv install neovim v0.1.4

$ vimenv global vim v0.1.4
$ vim
```

use system vi
```
$ vimenv global vim system
$ vimenv global neovim system
```
