# イライラ棒

## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
主人公キャラクターをキーボードで操作して障害物をよけながらステージを進み、最奥にあるアイテムをゲットする

## ゲームの遊び方
* 矢印キーで主人公を操作し、障害物をよける
* 障害物に触れると，ゲームオーバーとなる

## ゲームの実装
### 共通基本機能
* 主人公キャラクターの描画

### 担当追加機能
* スタート画面（担当：豊川巧真）
* クリア / ゲームオーバー画面（担当：打田雄輝）
* 障害物との衝突判定機能（担当：菊地　泰輝）
* 追加ギミック（担当：穂刈　陽太）
* ステージの構築（担当：長谷部　隼也）

### ToDo
- None
- None

### メモ
* スタート画面は講義資料を参考に作ってもらえれば大丈夫なはず...
* クリア / ゲームオーバー画面の処理は、ゲームが進行中かどうかを判定するbool型変数game_nowを使って処理してほしい
* 障害物との衝突判定は、衝突判定したらbool型変数game_now = Falseを返すようにしてほしい
* 追加ギミックは基本お任せするが、設計は引数に座標を引き渡すことで実装できるようにしてほしい
