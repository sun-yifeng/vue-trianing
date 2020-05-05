# 安装vue-devtools
参考
https://www.cnblogs.com/yihan123/p/10414884.html

1、拉取代码
git clone https://github.com/vuejs/vue-devtools.git

2、切换到master分支
D:\app\vue-devtools>git checkout master

3、安装依赖
D:\app\vue-devtools-dev>cnpm install

4、编译代码
D:\app\vue-devtools-dev>cnpm run build

5、更改配置
在shell\chrome\manifest.json中，将persistent的属性改为true

6、安装插件
把vue-devtools-dev > shells > chrome拖入浏览器

7、重启浏览器
