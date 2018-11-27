# example
**安装并升级node环境和light环境, 以及light的相关插件**

| pluginName | local versions | latest version |
| ::| :: | :: |
| lighting-plugin-jsnative | 1.0.12 | 1.0.12 |
| lighting-plugin-vue | 1.1.7 | 1.1.7 |
| lighting-plugin-native | 1.0.74 | 1.0.74 |
| lighting-plugin-type-vue | 1.1.3 | 1.1.3 |
插件已全部安装最新版本

**修改ip**

1. 将light-demo/http/http.js里的ip地址修改为本地ip
2. 将light-demo/lib/jqConfig.js里的ip地址修改为本地ip
 
**下载package.json定义的插件(这个步骤只有在第一次运行环境之前操作一次)**

1. cmd找到light-demo路径
2. cd lib
3. npm install

**运行后台文件**

1. cmd找到light-demo路径
2. cd http
3. node http

**运行项目**

1. cmd找到light-demo路径
2. light release -wb 3000

**运行效果**

![运行效果](https://i.imgur.com/U1l6GA8.png)

