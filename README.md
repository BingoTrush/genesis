<img src="./logo.svg" width="120">    

# Genesis


[![Build Status](https://travis-ci.org/fmfe/genesis.svg?branch=master)](https://travis-ci.org/fmfe/genesis)
[![Coverage Status](https://coveralls.io/repos/github/fmfe/genesis/badge.svg?branch=master)](https://coveralls.io/github/fmfe/genesis?branch=master)
[![npm](https://img.shields.io/npm/v/@fmfe/genesis-core.svg)](https://www.npmjs.com/package/@fmfe/genesis-core) 
[![npm](https://img.shields.io/npm/dm/@fmfe/genesis-core.svg)](https://www.npmjs.com/package/@fmfe/genesis-core)
[![npm](https://img.shields.io/npm/dt/@fmfe/genesis-core.svg)](https://www.npmjs.com/package/@fmfe/genesis-core)

一个简单而强大的Vue SSR框架

## 🚀 优势
- ✨ 编写简单的JS，就可以创建一个`SSR`项目    
- 🍀 基础灵活的API，可以在此基础上二次封装
- 🙅 开发依赖和生产依赖分包，在构建生产包时，应用更小化    
- 🤝 支持`Webpack module federation`
- 👍 支持`TypeScript`，生成`dts`和类型检查，开箱即用    
- 🛠 长期维护更新    

## 📚 文档
- [快速开始](./docs/zh-CN/quick-start.md)
    - [TS 运行时](./docs/zh-CN/quick-start.md#ts-运行时)
    - [HTTP 服务](./docs/zh-CN/quick-start.md#http-服务)
    - [简化命令](./docs/zh-CN/quick-start.md#简化命令)
    - [目录结构](./docs/zh-CN/quick-start.md#目录结构)
      - [genesis.ts](./docs/zh-CN/quick-start.md#genesists)
      - [genesis.build.ts](./docs/zh-CN/quick-start.md#genesisbuildts)
      - [genesis.dev.ts](./docs/zh-CN/quick-start.md#genesisdevts)
      - [genesis.prod.ts](./docs/zh-CN/quick-start.md#genesisprodts)
      - [tsconfig.json](./docs/zh-CN/quick-start.md#tsconfigjson)
      - [package.json](./docs/zh-CN/quick-start.md#packagejson)
- [管理HTML元数据](./docs/zh-CN/vue-meta.md)
    - [安装依赖](./docs/zh-CN/vue-meta.md#安装依赖)
    - [快速使用](./docs/zh-CN/vue-meta.md#快速使用)
    - [模板写入元数据](./docs/zh-CN/vue-meta.md#模板写入元数据)
    - [模板读取元数据](./docs/zh-CN/vue-meta.md#模板读取元数据)
- [@fmfe/genesis-core](./packages/genesis-core/README.md)
- [@fmfe/genesis-compiler](./packages/genesis-compiler/README.md)
- [@fmfe/genesis-app](./packages/genesis-app/README.md)
- [@fmfe/square](./packages/square/README.md)
- [@fmfe/genesis-lint](./packages/genesis-lint/README.md)
## 💻 本地开发
```bash
git clone git@github.com:fmfe/genesis.git
cd genesis

# 安装依赖
lerna bootstrap
```

### 命令说明
```bash
# 编译依赖包
yarn build:packages
# 运行例子
yarn dev
# 编译例子
yarn build
# 生产环境运行例子
yarn examples:start
# 例子类型检查
yarn type-check
# 代码风格检查
yarn lint
# JS 代码风格检查
yarn lint:js
# CSS 代码风格检查
yarn lint:css
```
### 例子说明
- 快速入门：http://localhost:3000
- `Webpack module federation`导入模块：http://localhost:3001
- `Webpack module federation`导出模块：http://localhost:3002
