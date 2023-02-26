# Tekken Frame Data ver0.4
※ [English README.md is here！](TODO)👈

## なぜ作ってるか

僕は最近鉄拳 7 という格闘ゲームにハマっててキャラの攻撃内容などがいろんなサイトに記載されてるけど若干見にくいので見やすくなるように自分で実装しました。

## 機能一覧

- フレーム表の項目の並び順（昇順・降順）を変更できる
<VIDEO HERE/>
- テーブルの項目をハイライトできる
<VIDEO HERE/>
- 技のコマンドを押すと技の動画が再生する
<VIDEO HERE/>


## 目的

Next.js と express.js と mysql の練習のために作成してます。

## Github Pages

https://perrym123.github.io/tekken-frame-data/

![alt text](./sampleData/ver0.3.1.gif)

## Getting Started

```
$ git clone git@github.com:PerryM123/tekken-frame-data.git
$ cd tekken-frame-data
$ yarn
$ yarn dev
```

## Techonogies being used

- フロント技術: NextJS
- サーバーサイド技術: express.JS (TODO: Add repo here)
- データベース: mysql

## prettier設定について

vscodeを使ってる方の場合、以下の設定をsettings.jsonに保存していただければと思います。

```
{
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  }
}
```
