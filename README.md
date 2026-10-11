# Flatpak 软件源

虹叙与星叙 Linux 版的 Flatpak 软件源，由 GitHub Pages 提供：https://wangmikuwang.github.io/flatpak/

安装（运行环境会自动从 Flathub 获取）：

```bash
flatpak install --user https://wangmikuwang.github.io/flatpak/hongxu.flatpakref
flatpak install --user https://wangmikuwang.github.io/flatpak/xingxu.flatpakref
```

之后用 `flatpak update` 即可获得新版本。也可以先添加整个软件源：

```bash
flatpak remote-add --user --if-not-exists wangmikuwang https://wangmikuwang.github.io/flatpak/wangmikuwang.flatpakrepo
```

软件源已签名，公钥包含在 `.flatpakref` 与 `.flatpakrepo` 文件中。源代码与安装包见 [HongXu-Linux](https://github.com/wangmikuwang/HongXu-Linux) 与 [XingXu-Linux](https://github.com/wangmikuwang/XingXu-Linux)。
