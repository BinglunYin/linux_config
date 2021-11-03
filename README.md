# linux_config


# a few notes:


## install python3 locally

```
$ cd 
$ mkdir tmp
$ cd tmp
$ wget https://www.python.org/ftp/python/3.6.5/Python-3.6.5.tgz
$ tar zxvf Python-3.6.5.tgz 
$ cd Python-3.6.5
$ ./configure --prefix=$HOME/opt/python-3.6.5
$ make
$ make install


$ cd ~/opt/bin
$ ln -s ~/opt/python-3.6.5/bin/python3  python3
$ ln -s ~/opt/python-3.6.5/bin/pip3  pip3
```


3.8.2 has a problem 
```
ModuleNotFoundError: No module named '_ctypes'
```




## pip3 install
```
pip3 install --user --upgrade  numpy  scipy  sympy  matplotlib
```

install myalloy_pkg from Github:     

```
pip3 install --user --upgrade    git+https://github.com/BinglunYin/myalloy_package.git    
```
or from a local folder:     
```
pip3 install --user -e   .  

```



