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
$ vimenv install vim v8.0.0046 --with-features=huge --enable-cscope --enable-fontset

# Mac
$ CC=gcc-4.9 vimenv install vim v8.0.0046 --with-features=huge  --enable-cscope --enable-fontset

$ vimenv global vim v8.0.0046
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

## install other version
vim
```
$ vimenv install vim HEAD
$ vimenv install vim <git hash id>
```

neovim
```
$ vimenv install neovim HEAD
$ vimenv install neovim <git hash id>
```


## install default option
vim
```
$ cat default-vim
--with-features=huge --enable-cscope --enable-fontset

$ vimenv install vim v8.0.0046
```
