# 朝までそれ正解 〜地元ルール〜

スマホ・PCのブラウザで遊べる、パーティーゲームアプリです。

## 遊び方

1. 中央の大きなボタンを押すとお題が出る（「◯から始まる、△△と言えば？」）
2. タイマーをスタートして、時間内にみんなで答えを考える
3. 全員で発表 → 一番お題に相応しくない答えをした人を指差しで「敗者」に
4. 右上の「🎯 ルーレットへ」から、敗者が飲む杯数（×0〜×3）をルーレットで決定！

## 公開（GitHub Pages）

このリポジトリは GitHub Pages で公開できます。

- 公開URL: https://fuji40254025.github.io/asasore/
- 設定: リポジトリの **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` / `(root)`** を選んで Save

## ファイル構成

| ファイル | 内容 |
|---|---|
| `index.html` | アプリ本体（HTML/CSS/JS すべて入り） |
| `gunshot.mp3` | ルーレット結果時の銃声 |
| `countdown.m4a` | タイマー残り5秒のカウントダウン音 |
| `roulette-bgm.mp3` | ルーレット画面のBGM |

お題ワードは `index.html` 内の `ODAI_WORDS` 配列で編集できます。
