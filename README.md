# Nwrt 固件下载

正式固件和配套网页资源包按机型发布。请在发布说明中核对路由器型号，再下载对应版本。[查看所有版本](https://github.com/N-wrt/nwrt-firmware-releases/releases)

## 京东云 AX1800 Pro

从 `2026.11.28.2` 起，每版提供两种镜像。首次安装 Nwrt 时，按适用于 AX1800 Pro 的首刷流程使用 `factory.bin`。已运行 Nwrt 的设备可在线升级，手动升级时选择 `sysupgrade.bin`。[下载最新固件](https://github.com/N-wrt/nwrt-firmware-releases/releases/latest)

在 **高级设置 → 系统设置** 中进入升级页面，点击 **检查更新**。请按当前已安装的版本选择菜单。

| 已安装版本 | 升级入口 |
| --- | --- |
| 2026.11.28.1 起 | 维护 → 在线升级 |
| 2026.11.27.2、2026.11.27.3 | 固件维护 → 在线更新 |

点击 **在线升级** 并确认后，路由器会自行下载、校验、刷写并重启。若旧版页面只有下载链接，可在 **本地升级** 中上传文件名以 `sysupgrade.bin` 结尾的镜像。

配套网页资源包可通过在线升级页面中的资源包管理入口安装。

## 更新目录

稳定版目录按设备板型列出固件，各机型可以独立更新。京东云 AX1800 Pro 的板型为 `jdcloud,ax1800-pro`。目录中尚无条目的机型，表示尚未发布正式版本。

- [稳定版更新目录](https://raw.githubusercontent.com/N-wrt/nwrt-firmware-releases/main/update-index.json)
- [目录签名](https://raw.githubusercontent.com/N-wrt/nwrt-firmware-releases/main/update-index.json.sig)
- [usign 验签公钥](./update.pub)
