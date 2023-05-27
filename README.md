# 概要
　Windows 向けの .exe と Linux 向けのバイナリーをそれぞれビルドして、同一の Release に公開するサンプルです。

# 補足
* 内部的には `gh` コマンドを利用しています。GitHub Actions から `gh` コマンドが使える現状を前提としています。

# 最新バイナリーファイルを指す URL
　以下のような URL で、常にそれぞれの最新版をダウンロードできます。

* Windows
```CMD
wsl.exe wget "https://github.com/mass10/gh-release-strategy-example-1/releases/latest/download/gh-release-strategy-example-1.exe"
```

* Linux
```bash
wget "https://github.com/mass10/gh-release-strategy-example-1/releases/latest/download/gh-release-strategy-example-1"
```
