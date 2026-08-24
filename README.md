# Pure Tokens Desktop Releases

This public repository is the official distribution surface for the proprietary
Pure Tokens desktop client.

> **当前状态：客户端仍在测试和调整中，暂不对外开放。**
>
> 我们正在进行最后一轮兼容性、稳定性和更新体验验证，确保正式发布后能够在不同设备和网络环境中稳定使用。你目前在 GitHub 页面看到的 Release、安装包或更新记录，均仅供团队内部测试与验证，不代表已正式发布，也请不要下载、安装或将其用于日常使用。
>
> 感谢你的关注和耐心等待。我们会在准备就绪后，通过官网和 GitHub Release 明确发布正式公告；在此之前，请以官网公告为准。
>
> **Current status: The desktop client is still being tested and refined and is not yet publicly available.**
>
> We are completing final compatibility, stability, and update-experience validation across different devices and network environments. Any GitHub Releases, installers, or update notes currently visible are for internal testing and verification only. They are not a public release and should not be downloaded, installed, or used for day-to-day work.
>
> Thank you for your interest and patience. When the client is ready, we will clearly announce its public availability on the official website and through GitHub Releases. Until then, please rely on the official website for status updates.

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
