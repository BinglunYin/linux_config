# linux_config


# a few notes:


## install python3 locally

```
$ cd ~
$ mkdir tmp
$ cd tmp
$ wget https://www.python.org/ftp/python/3.8.1/Python-3.8.1.tgz
$ tar zxvf Python-3.8.1.tgz 
$ cd Python-3.8.1 
$ ./configure --prefix=$HOME/opt/python-3.8.1
$ make
$ make install


$ cd ~/opt/bin
$ ln -s ~/opt/python-3.8.2/bin/python3  python3
$ ln -s ~/opt/python-3.8.2/bin/pip3  pip3
```


