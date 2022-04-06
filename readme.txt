在x86 PC Linux 环境下按如下操作：
1、cat rk3399pro_Android8.1.tar.gz.* >rk3399pro_Android8.1.tar.gz 
2、tar -zxvf rk3399pro_Android8.1.tar.gz,解压缩后生成rk3399pro_Android8.1 目录
2、cd rk3399pro_Android8.1
3、cp device/rockchip/rk3399pro/build.sh ./
4、./build.sh -b prox   (开发板为tb-rk3399prox / tb-rk3399proxs)
或者./build.sh -b prod  (开发板为tb-rk3399prod / tb-rk3399prods)

getprop | grep "model"