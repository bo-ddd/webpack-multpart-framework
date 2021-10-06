# 🚀 project name : webpack-multpart-framework

### 多页面webpack环境架构；

### 使用说明：
1. 新增模块时，需要在webpack.config.js的 getConfig 入参中,配置上模块的文件夹名称,
  eg: 
  ```javascript
    const conf = getConfig({
      modules:['home','mine']  //新增模块
    });
  ```


### 构建
npm run build

