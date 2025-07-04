# マインクラフト用画像変換ツール（Made of Blocks テクスチャ参考）

このツールは、マインクラフトのテクスチャなどを「色辞書」に基づいてピクセル単位で色変換・拡大するためのWebアプリケーションです。

---

## 特徴

- ダークモード（以外に非）対応のシンプルで使いやすいUI
- 左側に「色辞書用画像」をドラッグ＆ドロップし、指定サイズのPNG画像から平均色を抽出して登録
- 右側に「反映する画像」をドラッグ＆ドロップすると、左側の色辞書の中から最も近い色に置換して拡大表示
- 透明ピクセルは透明のまま、半透明ピクセルは透明度を維持しつつ色を置換
- 変換後の画像はブラウザ上に表示され、PNG形式で保存可能

---

## 使用方法

1. 左側の「色辞書用画像」のサイズ制限を設定（例：16×16）
2. 指定サイズのPNG画像を左側のドロップエリアに複数ドラッグ＆ドロップして色辞書を作成
3. 右側のドロップエリアに変換したいPNG画像をドラッグ＆ドロップ
4. 左側の幅の数値を拡大倍率として使用し、画像を変換・拡大します
5. 変換後の画像が下のキャンバスに表示され、リンクから保存可能

---

## 参考

- このツールは以下のテクスチャパックのスタイルを参考に作成されました  
  [Made of Blocks テクスチャ - Planet Minecraft](https://www.planetminecraft.com/texture-pack/textures-made-of-blocks/)

---

## 開発について

- 本ツールのコードはAI（ChatGPT）によって生成されました。  
- 利用者の要望に基づき、柔軟にカスタマイズ可能です。

---

## 動作環境

- モダンなWebブラウザ（Chrome, Firefox, Edge等）  
- インターネット接続不要（ローカルで完結）

---

## ライセンス

このコードは自由に使用・改変可能ですが、元のツールへのリスペクトをお願いいたします。

---

## 問い合わせ

不具合や要望などありましたら、ぜひご連絡ください。

---

### 作成者

AI (ChatGPT) とユーザーの共同作成によるツールです。

