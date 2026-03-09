# Massage NoMosaic Mod

Massageの表現を修正します。
UE4SSフレームワークを利用して動作します。

## 導入方法 (Installation)

1. リリースページから `Massage_NoMosaic.zip` をダウンロードして解凍します。
2. 解凍して出てきた以下の2つをコピーしてください。
   - `dwmapi.dll` （ファイル）
   - `ue4ss` （フォルダ）
3. コピーしたものを、ゲームのインストールフォルダ内にある以下の階層に貼り付け（上書き）します。

   👉 **配置場所: `Massage\Binaries\Win64\`**

   ※注意※
   一番最初に見つかる `Massage.exe` があるフォルダではありません。
   さらに奥に進んだ `Massage-Win64-Shipping.exe` があるのと同じフォルダに配置してください。


### 【正しいフォルダ配置のイメージ】
```text
📁 (Massageをインストールしたフォルダ)
 ┗ 📁 Massage
    ┗ 📁 Binaries
       ┗ 📁 Win64
          ┣ 📄 Massage-Win64-Shipping.exe (元からあるゲーム本体)
          ┣ 📄 dwmapi.dll (今回入れたファイル)
          ┗ 📁 ue4ss (今回入れたフォルダ)
```


## アンインストール方法 (Uninstallation)

導入時に配置した `dwmapi.dll` と `ue4ss` フォルダを削除するだけで、元のモザイクありの状態に戻ります。

## クレジット・利用技術
- Unreal Engine 4 Scripting System (UE4SS) v3.0.1

