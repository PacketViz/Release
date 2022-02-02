# 以下のURLからダウンロード
### mac
https://github.com/PacketViz/Release/releases/download/mac/PacketViz.command

### windows
https://github.com/PacketViz/Release/releases/download/windows/PacketViz.exe

# macのエラー
## セキュリティエラー
macの場合以下のようなエラーが出ることがあります。

![cannot_open](./mac_cannot_open.png)



その場合、システム環境設定の「セキュリティとプライバシー」を開いて、「このまま開く」ボタンを押していただくと、開くことができます。

![setting](mac_security_setting.png)

## ダークモード非対応
macのダークモードには非対応なので、ライトモードにしてお使いください。

## 権限エラー
以下のコマンドを実行してください。
```
chmod a+x PacketViz.command
```
