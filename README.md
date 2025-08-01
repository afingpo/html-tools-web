# Scratch游戏静态网站

这是一个用于托管和展示Scratch游戏的静态网站模板。

## 项目结构

- `index.html`: 网站首页
- `game-manifest.json`: 游戏配置文件
- `_headers`: Netlify特殊配置文件
- `assets/`: 静态资源目录
- `src/`: Scratch游戏HTML文件目录

## 使用方法

1. 将Scratch导出的HTML文件放入`src/`目录
2. 在`game-manifest.json`中添加游戏信息
3. 将项目推送到GitHub仓库
4. 在Netlify导入该仓库进行部署

## 自定义

- 修改`index.html`中的CSS来自定义样式
- 在`assets/`中添加自定义图片资源
- 更新`game-manifest.json`配置游戏信息