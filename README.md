# hello-libbpfgo

https://mozillazg.com/tag/libbpfgo.html


# hello-libbpfgo

https://mozillazg.com/tag/libbpfgo.html


run with golang

```
wget https://go.dev/dl/go1.19.1.linux-amd64.tar.gz

sudo rm -rf /usr/bin/go && sudo tar -C /usr/bin/ -xzf go1.19.1.linux-amd64.tar.gz

export PATH=$PATH:/usr/bin/go/bin

go version 

```

edit bashrc 

```
vim ~/.bashrc 


#!/bin/bash
export PATH=$PATH:/usr/bin/go/bin
export PATH=$PATH:/home/wenhui.zhang/llvm-project/build/bin


source ~/.bashrc 
```

test

```
cd hello-libbpfgo/01-hello-world
make
```


# sample bashrc
```
#!/bin/bash
export PATH=$PATH:/usr/bin/go/bin
export PATH=$PATH:/home/wenhui.zhang/llvm-project/build/bin
```





## setup develop env

```
$ vagrant plugin install vagrant-env
$ cp .env.example .env
$ vagrant up
```
