## WindowsにSonic Piをインストールする

- Webブラウザで [sonic-pi.net](https://sonic-pi.net/)に移動します。

- ページの下の方にある**Windows**ボタンをクリックします。

![ダウンロード](images/download-buttons.png)

- **Windows 10 (64 bit) Download MSI Installer**ボタンをクリックします。.

![msi](images/msi-installer.png)

- ダウンロードフォルダーにある `msi`ファイルをダブルクリックします。.

![windows1](images/windows1.png)

- 利用規約に同意して**Install**を押します。.

![windows2](images/windows2.png)

- **Finish**を押してインストールを完了し、Sonic Piを起動します。

![windows3](images/windows3.png)


## macOSにSonic Piをインストールする

- Webブラウザで[sonic-pi.net](https://sonic-pi.net/)に移動します。

- ページの下の方にある**macOs**ボタンを押します。

![ダウンロード](images/download-buttons.png)

- **Download**ボタンを押します。

![ダウンロード](images/download.png)

- ダウンロードフォルダにダウンロードした`.dmg`ファイルをクリックします。

![macOS1](images/macOS1.png)

- `Sonic Pi.app`ファイルをクリックします。

![macOS2](images/macOS2.png)

- Finderでアプリケーションフォルダを開きます。`Ctrl`キーを押しながら`Sonic Pi.app`ファイルをクリックし、<1>開く</1>をクリックします。

![macOS3](images/macOS3.png)

- プロンプトが表示されたら**開く**を押します。

![macOS4](images/macOS4.png)

## Raspberry PiにSonic Piをインストールする

- `Ctrl`、`Alt`、`T`キーを同時に押します。ターミナルウィンドウが開きます。

- ターミナルウィンドウで以下を入力します：

```bash
sudo apt update && sudo apt install sonic-pi -y
```

