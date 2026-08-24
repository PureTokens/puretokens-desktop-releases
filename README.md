# Pure Tokens Desktop Releases

This public repository is the official distribution surface for the proprietary
Pure Tokens desktop client.

> **当前状态：客户端仍在测试和调整中，暂不对外开放。当前 GitHub Release 资产仅用于内部测试，请勿下载或作为正式版本使用。可用版本发布时，会在官网和 GitHub Release 单独公告。**
>
> **Current status: The desktop client is still under testing and adjustment and is not publicly available. Current GitHub Release assets are for internal testing only. Do not download or treat them as a production release. Availability will be announced on the official website and GitHub Releases.**

- Official download page: <https://puretokensx.com/switch>
- Installer and updater artifacts: [GitHub Releases](https://github.com/yanyansay/puretokens-desktop-releases/releases)
- Stable updater manifest: `stable/latest.json`
- Internal prerelease updater manifest: `beta/latest.json`

The application source code is not published in this repository. Update bundles
are verified by the Tauri updater public key committed in
`updater-public-key.txt`. The matching private key is held outside GitHub and is
never uploaded to this repository.

No installer is considered available until its release asset, `.sig` file,
SHA-256 checksum, and matching manifest entry have all been published.
