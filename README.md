# Nwrt 固件下载

正式固件和配套网页资源包按机型发布。请在发布说明中核对路由器型号，再下载对应版本。[查看所有版本](https://github.com/N-wrt/nwrt-firmware-releases/releases)

## 京东云 AX1800 Pro

进入 LuCI 的 **高级设置 → 系统设置 → 固件维护 → 在线更新**，点击 **检查更新**。从 **2026.11.27.2** 起，选择 **在线升级** 并确认后，路由器会自行下载、校验、安装固件并重启。若当前页面只有下载链接，可在 **本地升级** 中上传文件名以 `sysupgrade.bin` 结尾的镜像。

配套的 `asuswrt-www_*.tar.gz` 可在 **一般设置 → 设备状态 → 华硕网页资源包** 安装。

## 更新目录

稳定版目录按设备板型列出固件，各机型可以独立更新。京东云 AX1800 Pro 的板型为 `jdcloud,ax1800-pro`。目录中尚无条目的机型，表示尚未发布正式版本。

- [稳定版更新目录](https://raw.githubusercontent.com/N-wrt/nwrt-firmware-releases/main/update-index.json)
- [目录签名](https://raw.githubusercontent.com/N-wrt/nwrt-firmware-releases/main/update-index.json.sig)
- [usign 验签公钥](./update.pub)
