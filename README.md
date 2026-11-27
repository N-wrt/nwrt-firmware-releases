# Nwrt 固件下载

正式固件和配套网页资源包按机型发布。请在发布说明中核对路由器型号，再下载对应版本。[查看所有版本](https://github.com/N-wrt/nwrt-firmware-releases/releases)

## 京东云 AX1800 Pro

已安装 Nwrt 的设备可在 LuCI 的 **系统管理 → 固件维护** 上传文件名以 `sysupgrade.bin` 结尾的镜像。配套的 `asuswrt-www_*.tar.gz` 可在 **设备状态 → 华硕网页资源包** 安装。

## 更新目录

稳定版目录按设备板型列出固件，各机型可以独立更新。京东云 AX1800 Pro 的板型为 `jdcloud,ax1800-pro`。目录中尚无条目的机型，表示尚未发布正式版本。

- [稳定版更新目录](https://raw.githubusercontent.com/N-wrt/nwrt-firmware-releases/main/update-index.json)
- [目录签名](https://raw.githubusercontent.com/N-wrt/nwrt-firmware-releases/main/update-index.json.sig)
- [usign 验签公钥](./update.pub)
