# sing-box-builder

自动编译 [sing-box](https://github.com/SagerNet/sing-box) 的 GitHub Actions 工作流。

## 构建平台

- Linux (x64)
- Android (arm64)
- macOS (arm64)

## 编译标签

`with_quic` `with_utls` `with_clash_api` `with_gvisor` `with_cloudflared`

工作流每天 UTC 02:00 自动拉取最新版本编译，也可手动触发。会同时编译正式版和最新版（含预发布），分别创建独立的 Release。
