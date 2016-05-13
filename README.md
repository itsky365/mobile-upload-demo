### mobile-upload-demo

移动端 Web 传图示例

#### 运行

```
git clone https://github.com/progrape/mobile-upload-demo.git
cd mobile-upload-demo
npm install
npm start
```

服务端接收程序是 `koa` 写的, 确保你的 `node` 版本可以运行 `koa`

浏览器打开 `http://localhost:3000`, 选择图片, 点击上传, 图片会保存到 `public/upload` 目录.