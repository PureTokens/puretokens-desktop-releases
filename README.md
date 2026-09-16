# Pure Tokens Switch

### 让 AI 客户端配置更简单。

Pure Tokens Switch 桌面客户端现已公开发布，支持 macOS 与 Windows。
在这里获取官方安装包、版本说明和更新文件。

**[官网下载](https://puretokensx.com/switch) · [最新版本](https://github.com/PureTokens/puretokens-desktop-releases/releases/latest) · [历史版本](https://github.com/PureTokens/puretokens-desktop-releases/releases)**

## 选择你的安装包

| 系统 | 设备 | 安装文件 |
| --- | --- | --- |
| macOS | Apple Silicon，M 系列芯片 | 文件名以 `_aarch64.dmg` 结尾 |
| macOS | Intel 芯片 | 文件名以 `_x64.dmg` 结尾 |
| Windows | x64 | 文件名以 `_x64-setup.exe` 结尾 |

不确定该选哪个？前往[官网下载页](https://puretokensx.com/switch)查看安装说明。
Release 中的 `.app.tar.gz` 和 `.sig` 是自动更新归档与签名文件，不是需要单独打开的安装程序。

## 更新与校验

- 正式版可在客户端设置中检查更新；检查或安装失败时，可从官网下载页获取安装包重新安装。
- 每个 Release 提供版本说明和 SHA-256 校验和，请只使用官方渠道发布的文件。
- 自动更新包使用 Tauri Updater 签名校验完整性。当前社区安装包未经过 Apple Developer ID 签名或公证，也未使用 Windows Authenticode 签名；系统可能显示安全提示，请核对来源并遵循设备的安全策略。

## 关于这个仓库

这里只分发 Pure Tokens Switch 的安装包和更新文件，**不公开应用源码**。
Pure Tokens Switch 为专有软件。

Stable 更新清单位于 [`stable/latest.json`](https://github.com/PureTokens/puretokens-desktop-releases/blob/main/stable/latest.json)，更新验证公钥位于 [`updater-public-key.txt`](https://github.com/PureTokens/puretokens-desktop-releases/blob/main/updater-public-key.txt)。本仓库不包含更新签名私钥。

---

## English

### Simpler setup for your AI clients.

Pure Tokens Switch is publicly available for macOS and Windows.
This is the official repository for installers, release notes, and update files.

**[Download](https://puretokensx.com/switch) · [Latest release](https://github.com/PureTokens/puretokens-desktop-releases/releases/latest) · [Release history](https://github.com/PureTokens/puretokens-desktop-releases/releases)**

### Choose your installer

| Platform | Hardware | Filename ends with |
| --- | --- | --- |
| macOS | Apple Silicon, M-series chips | `_aarch64.dmg` |
| macOS | Intel | `_x64.dmg` |
| Windows | x64 | `_x64-setup.exe` |

See the [download page](https://puretokensx.com/switch) for installation instructions.
The `.app.tar.gz` and `.sig` files are update archives and signatures, not standalone installers.

### Updates and security

- Check for updates in the production app's settings. If checking or installation fails, download an installer from the official download page.
- Each release includes release notes and SHA-256 checksums. Use files from official sources only.
- Tauri Updater signatures verify update integrity. Community installers are not Apple Developer ID signed or notarized, and are not Windows Authenticode signed. Your system may display a security warning; verify the source and follow your device's security policy.

### Repository scope

Pure Tokens Switch is proprietary software. This repository distributes installers and update files; **application source code is not published here**.

The Stable update manifest is [`stable/latest.json`](https://github.com/PureTokens/puretokens-desktop-releases/blob/main/stable/latest.json).
The verification key is [`updater-public-key.txt`](https://github.com/PureTokens/puretokens-desktop-releases/blob/main/updater-public-key.txt).
No update-signing private key is stored in this repository.
