# AI Passport Studio

私人 AI Passport 固件库，可在浏览器中保存、下载并通过 Web Serial 一键烧录 ESP32 固件。

## 使用

1. 使用桌面版 Chrome 或 Edge 打开网站。
2. 上传编译后的合并 `.bin` 固件，并填写烧录地址（通常为 `0x0`）。
3. 用 USB 连接 AI Passport。
4. 点击“一键烧录”，选择 Espressif USB JTAG/serial 设备。

固件保存在当前浏览器的 IndexedDB 中，不会上传到服务器。

## 本地预览

直接打开 `index.html`，或启动任意静态文件服务器。
