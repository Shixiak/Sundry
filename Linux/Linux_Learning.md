# Linux_Learning

## Installation

### Conventional installation methods

```shell
sudo apt install gdebi  # Most software can be installed this way
```

### methods of ".deb"

> How to install ".deb" : https://zhuanlan.zhihu.com/p/339632982

``` shell
# method 2
# Use Gdebi to install ".deb" file
# But at first, maybe you need to install Gdebi
# After you completed the installation, you can finish it through the visual interface of this tool

# method 3


```

## Uninstallation

> Except(how to find exact name) : https://blog.csdn.net/Hyaloidz/article/details/80144555  
> Screen apps : https://blog.csdn.net/jiayoudangdang/article/details/79943065  

```shell
sudo apt remove --purge packagename  # Delete configuration files while uninstalling software
sudo apt-get remove packagename  # Just remove software

dpkg --get-selections | grep fuzzy_name  # screening of possible app 
```

## Cleaning up residual files

> https://blog.csdn.net/Hyaloidz/article/details/80144555  

```shell
# file location
# var/cache/apt/archives

sudo apt clean
```

## Create .venv

> url : https://blog.csdn.net/weixin_44244190/article/details/134075563

## Screen

> tutorials : https://zhuanlan.zhihu.com/p/405968623
