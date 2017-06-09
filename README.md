# toolc-main

## Environment
1. Linux-86_64
2. Darwin-x86_64  

If you are different OS, please build and push the [toolc-dist](https://github.com/ISSKJ/toolc-dist) repository. 


## How to install
```
$ ./toolc install
```
Add the following line to $PATH
export PATH=$PATH:/$(YOUR_HOME_DIRECTORY)/.toolc/toolc-dist/$(YOUR_OS_ARCHITECTURE)

## How to build (For a distributor)
```
$ git clone https://github.com/ISSKJ/toolc-dist
$ cd toolc-dist
$ ./build.sh build
```
And push the [toolc-dist](https://github.com/ISSKJ/toolc-dist) repository. 
