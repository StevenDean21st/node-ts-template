# README

通用 Node.js Typescript 项目模板。

使用模板前先运行`npm run init`安装项目开发依赖。

## NPM 脚本

```bash
npm run init        # 安装项目开发依赖
npm run dev         # 启动开发模式
npm run dev:nowatch # 启动开发模式，但不进行热重载
npm run build       # 构建项目
npm run start       # 构建后启动项目
```

## Typescript 配置

项目模板中的 Typescript 默认配置为构建 ESNext 标准的 JavaScript 代码，使用 ES Module，并启用严格模式。

其中，源代码目录为`/lib`，构建输出目录为`/bin`。

JavaScript 兼容性相关配置已设置，可以直接导入 JavaScript 包。

## Nodemon 配置

`/nodemon.json`中默认配置了监视和忽略目录，使用`npm run dev`来启动开发模式。

## TS Node 配置

`/tsconfig.json`中默认包含`ts-node`的相关配置。

## ignore 文件配置

模板中包含`.gitignore`和`.npmignore`文件，内容使用 Node.js 忽略文件模板，并默认配置了对常用 IDE 的项目配置文件目录的忽略。