## 功能
使用su 0 执行命令，同时保持termux的环境变量 

## 使用方法
envsudo [COMMAND [ARG...]]

## 为什么要写这个东西
我的魅族16xs自带的su命令功能极为有限   
只支持"su [UID[,GID[,GID2]...]] [COMMAND [ARG...]]"  
直接用su 0 执行命令不会保持termux的环境变量,跑不了termux的命令   
使用termux的tsu或sudo会报错 "/system/xbin/su: invalid uid/gid '-c'"  
于是就有了这个简陋的小脚本  
  
