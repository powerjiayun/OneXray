# OneXray

## 应用介绍

关注我们的 Telegram 频道：[OneXray](https://t.me/OneXrayApp)

[文档站](https://onexray.com)

## 下载

| 操作系统 | 版本                                  | CPU 架构             | 安装包格式 | 下载链接                                                                                                                   |
| -------- | ------------------------------------- | -------------------- | ---------- | -------------------------------------------------------------------------------------------------------------------------- |
| Windows  | Windows 10, Windows 11                | x86_64               | exe        | [OneXray-windows-amd64.exe](https://github.com/OneXray/OneXray/releases/latest/download/OneXray-windows-amd64.exe)         |
| Windows  | Windows 10, Windows 11                | x86_64               | zip        | [OneXray-windows-amd64.zip](https://github.com/OneXray/OneXray/releases/latest/download/OneXray-windows-amd64.zip)         |
| Android  | Android 9.0 及以上                    | arm64, x86_64        | aab        | Google Play Store                                                                                                          |
| Android  | Android 9.0 及以上                    | arm64, x86_64        | apk        | [OneXray-android-universal.apk](https://github.com/OneXray/OneXray/releases/latest/download/OneXray-android-universal.apk) |
| iOS      | iOS 15.0 及以上                       | arm64                | ipa        | [OneXray-ios.ipa](https://github.com/OneXray/OneXray/releases/latest/download/OneXray-ios.ipa)                             |
| iOS      | iOS 15.0 及以上                       | arm64                | ipa        | [App Store](https://apps.apple.com/us/app/croxray/id6745059673)                                                            |
| macOS    | macOS 12.0 及以上                     | Apple silicon, Intel | pkg        | [Mac App Store](https://apps.apple.com/us/app/croxray/id6745059673)                                                        |
| Linux    | Ubuntu 20.04 及以上, Debian 11 及以上 | x86_64               | deb        | [OneXray-linux-x86_64.deb](https://github.com/OneXray/OneXray/releases/latest/download/OneXray-linux-x86_64.deb)           |
| Linux    | Ubuntu 20.04 及以上, Debian 11 及以上 | x86_64               | zip        | [OneXray-linux-x86_64.zip](https://github.com/OneXray/OneXray/releases/latest/download/OneXray-linux-x86_64.zip)           |
| Linux    | Ubuntu 20.04 及以上, Debian 11 及以上 | arm64                | deb        | [OneXray-linux-aarch64.deb](https://github.com/OneXray/OneXray/releases/latest/download/OneXray-linux-aarch64.deb)         |
| Linux    | Ubuntu 20.04 及以上, Debian 11 及以上 | arm64                | zip        | [OneXray-linux-aarch64.zip](https://github.com/OneXray/OneXray/releases/latest/download/OneXray-linux-x86_64.zip)          |

## 使用注意

### iOS

若您没有 Apple ID ，或您的 Apple ID 无法下载 OneXray ，您可以下载 **OneXray-ios.ipa** ，然后使用 [AltStore](https://altstore.io/) 或
其他第三方工具进行安装。

### Linux

若您使用 zip 包，您需要进行如下设置才可正常使用 OneXray。

执行指令前请确认目录。

```shell
sudo setcap cap_net_admin+epi onexray/bin/tun
sudo setcap cap_net_admin+epi onexray/bin/route
```
