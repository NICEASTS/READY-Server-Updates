# READY 服务器浏览器更新信息

**BY TAKI**  
有问题或意见反馈请联系QQ2514962562。

当前发布版本：`1.0.0`。

## 修改版本提示

编辑 [version.txt](https://github.com/NICEASTS/READY-Server-Updates/edit/main/version.txt)，文件内容只保留三段数字版本号，例如 `1.0.1`，提交到 `main` 分支。软件启动时、每隔 5 分钟以及点击“检查更新”时都会检查；远端有效版本与 EXE 内置版本不同就提示需要更新。GitHub Raw 缓存可能使提示延后几分钟。

Raw 地址：https://raw.githubusercontent.com/NICEASTS/READY-Server-Updates/main/version.txt

修改此文件只改变更新提示，不会自动生成或下载安装新 EXE。发布新版需要同步修改本地 `BuildConfig.h` 和版本资源，重新编译并保护 EXE 与配套桥接 DLL。

本仓库只保存公开版本信息。服务器源码和本地构建产物在开发项目中维护。
