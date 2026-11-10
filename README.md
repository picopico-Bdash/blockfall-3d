# ブロックフォール 3D

Three.js で作った 3D 落ち物ブロックパズルゲームです。ブラウザだけで遊べます。

## 遊ぶ

👉 https://picopico-bdash.github.io/blockfall-3d/

## 画質設定

タイトル画面の「画質」ボタンで **自動 / 高画質 / 軽量** を切り替えられます。
ブラウザのハードウェアアクセラレーション（グラフィックカード）が無効な環境では、自動で軽量モードになります
（透過ガラス・発光・影をやめ、Blender でレンダリングしたガラスの質感画像 `matcap_glass.jpg` で描画）。

## ローカルで動かす

`index.html` をブラウザで開くか、簡易サーバーで配信してください。

```bash
npx serve .
```

## 技術

- HTML / CSS / JavaScript（単一ファイル）
- [three.js](https://threejs.org/) r158（CDN 読み込み）
