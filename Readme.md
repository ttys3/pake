# Pake

> 用 Rust 来打包你的 App，底层使用 tauri，当前支持微信读书，有更多想法，欢迎提issue。

## 下载地址

- 微信读书：<http://tw93.fun/images/app/WeRead.dmg>

## 展示效果

![](https://cdn.fliggy.com/upic/N1coVx.gif)

## 开发步骤

```shell
//安装依赖
npm i

//本地调试
npm run dev

//打包app
npm run build
```

## 打一个新的包

1. 修改 src-tauri 目录下的 tauri.conf.json 中的 productName、icon、title、identifier 这4个字段
2. 修改 src-tauri src 目录下的 main.rs 中的 with_url 字段为你需要打包网页的地址
3. npm run build 即可