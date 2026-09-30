# DeepWork 安装说明

当前发布版本：2.0.16。安装文件：`DeepWork-2.0.16-x64-Setup.exe`，适用于 Windows x64。

1. 在 [Releases](../../releases) 中下载 EXE 和 `SHA256SUMS.txt`。在 PowerShell 中运行 `Get-FileHash -Algorithm SHA256 -LiteralPath '下载文件的完整路径'` 并比对校验值。
2. 双击 EXE，按安装向导选择当前用户或所有用户安装，并按需要选择安装目录。
3. 从开始菜单或桌面快捷方式启动 DeepWork。首次启动后按应用提示完成工作环境配置。

卸载应用时用户数据会保留。该安装包没有 Windows 发布者代码签名，系统可能提示“未知发布者”；请确认下载地址位于 `github.com/vlaipro/DeepWork-releases`，且文件校验值一致。原生窗口、安装升级及目标电脑环境仍需在实际设备上验证。
