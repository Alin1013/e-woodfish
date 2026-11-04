# 电子木鱼

这是一个无外部依赖的单页网页。庭院氛围可在晨雾、暮色和夜禅之间切换；点击木鱼会让累计功德加一，并播放“功德加一”中文女声。语音由 macOS Tingting 本机语音合成生成，音频随网页一起发布。功德数和场景偏好保存在当前浏览器中，不会跨设备同步。

## 发布到 GitHub Pages

1. 在 GitHub 新建一个公开仓库，例如 `e-woodfish`。
2. 上传本目录中的 `index.html` 和 `gongde-plus-one.wav`，并保持两者在仓库根目录同级。
3. 打开仓库的 **Settings → Pages**，将 **Build and deployment** 设为 **Deploy from a branch**，分支选 `main`、目录选 `/ (root)` 并保存。
4. 等待 Pages 完成发布，访问 `https://alin1013.github.io/e-woodfish/`。

发布完成后，该地址可以填入钉钉的“插入链接”。在仓库尚未创建并启用 Pages 前，这只是预期地址，还不能访问。GitHub Pages 首次发布可能需要几分钟。
