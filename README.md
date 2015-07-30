# GGTinypng
批量压缩png和jpg图片python脚本
减少图片50%以上的大小，肉眼看不出差别。减量不减质。
图片数量少的话可以在tinypng.com上试一下。看下效果。

已经支持子文件夹里面的图片，会按原始的相对路径存放到输出文件夹内

7.30 新加功能：一条命令压缩整个项目内的图片。

显著降低app的大小

## 使用方法
可以使用alias来简化命令
python3 tinypng.py -i <picDocPath> -o <outputDocPath>

 -o 参数可以为空，因为要遍历picDocPath子文件夹 所以默认outputDocPath改为picDocPath父目录
 内的outputTinypng文件夹，与picDocPath同级。

 7.30 新参数：python3 tinypng.py -r <项目路径或者项目内某个图片文件夹的路径>

 -r 参数会压缩文件夹内的图片并替换原图片

去 https://tinypng.com/developers 免费申请自己的key 每key每月免费压缩500个图

默认并发数为10 可以自己调整

##to do

如果有时间的话可能会做成处理mac程序或者xcode插件。不过短时间内不会，因为我自己用的话
脚本就足够了。
