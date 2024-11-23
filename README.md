# C-Compiler
https://www.sigbus.info/compilerbook を参考にして作ったCコンパイラ  

## Environment

Linux / [WSL2](https://learn.microsoft.com/ja-jp/windows/wsl/install)  
```
$ sudo apt update
$ sudo apt install -y gcc make git binutils libc6-dev
```

## Usage

### build

```
$ git clone https://github.com/nk12U/C-Compiler.git  
$ cd 9cc  
$ make
```

### test

```
$ ./test.sh
```

## Online Compiler

C言語のソースコードをアセンブリに変換してくれるオンラインコンパイラ  
[Compiler Explorer](https://godbolt.org/)
