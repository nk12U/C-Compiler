# C-Compiler
https://www.sigbus.info/compilerbook を参考にして作ったCで書かれたCコンパイラ  

## Environment

[WSL2](https://learn.microsoft.com/ja-jp/windows/wsl/install)  
```
$ sudo apt update
$ sudo apt install -y gcc make git binutils libc6-dev
```

## How to use

### build
```
$ git clone https://github.com/nk12U/C-Compiler  
$ cd 9cc  
$ make
```

### test

`$ ./test.sh`

## Online Compiler

C言語のソースコードをアセンブリに変換してくれるオンラインコンパイラ  
[Compiler Explorer](https://godbolt.org/)
