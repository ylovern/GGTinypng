# GGTinypng
批量压缩png和jpg图片python脚本

已经支持子文件夹里面的图片，会按原始的相对路径存放到输出文件夹内

## 使用方法

python3 tinypng.py -i picDocPath -o outputDocPath

 -o 参数可以为空，因为要遍历picDocPath子文件夹 所以默认outputDocPath改为picDocPath父目录
 内的outputTinypng文件夹，与picDocPath同级。

去 https://tinypng.com/developers 免费申请自己的key 每key每月免费压缩500个图

默认并发数为10 可以自己调整

##to do

如果有时间的话可能会做成处理mac程序或者xcode插件。不过短时间内不会，因为我自己用的话
脚本就足够了。
