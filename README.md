# neovim-config
- Clone this repo and replace the contents (if directory present create it) of `~/.config/nvim/lua/custom`. In windows `C:\Users\<ur_username>\AppData\Local\nvim\lua\custom`.

## Prerequisite
- Install neovim 0.8.0 or higher (right now debian repository has old one, so download new one)
- Install nvchad.
- Copy all the configs
- In neovim `:MasonInstallAll`
- Additional tools

## Go
```
go install mvdan.cc/gofumpt@latest
go install  github.com/incu6us/goimports-reviser/v3@latest
go install github.com/segmentio/golines@v0.9.0

$ git clone https://github.com/go-delve/delve
$ cd delve
$ go install github.com/go-delve/delve/cmd/dlv

Insdie neovim
:MasonInstallAll
:Lazy  // and then sync the package
```

## python
```
:TSInstall python
:MasonInstallAll
:Lazy  // and sync the package
// Its meant for linux so might not work as expected
```

For rust https://www.youtube.com/watch?v=mh_EJhH49Ms&ab_channel=DreamsofCode
Run some command first
$ rustup component add rust-analyzer
$ apt install lldb
Inside neovim 
:Lazy install
:MasonInstallAll

## Reference
 - From the video https://www.youtube.com/watch?v=i04sSQjd-qo&t=193s&ab_channel=DreamsofCode
 - Python config https://github.com/dreamsofcode-io/neovim-python
