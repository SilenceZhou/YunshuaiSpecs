# YunshuaiSpecs

一、使用：

1、先添加私有库的配置文件
```
   pod repo add YunshuaiSpecs https://github.com/SilenceZhou/YunshuaiSpecs.git
```

2、搜索 
```
   pod search LeftChangeIconTextField
```
3、在Podfile文件里面添加：
source 'https://github.com/SilenceZhou/YunshuaiSpecs.git'
   
   

二、制作自己的私有库

参考链接： 
http://www.jianshu.com/p/7559242455d5

如何创建私有Pod

创建过程

1.创建私有Spec Repo（首先在git/码云上创建私有库）
 ```
 pod repo add YunshuaiSpecs https://github.com/SilenceZhou/YunshuaiSpecs.git
 ```
 
 2.创建自己的私有库Lib（自行学习）
 
 3.在本地私有库podspec同级目录下进行如下操作，上传私有库，制作完毕
 ```
   pod repo push YunshuaiSpecs LeftChangeIconTextField.podspec
```




