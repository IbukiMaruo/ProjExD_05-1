# 勇者こうかとん
## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
主人公キャラクターこうかとんがUFOの親玉と戦う

## ゲームの実装
###共通基本機能
* 壁の判定を確認する関数
* こうかとんの方角を確認する関数
* 主人公キャラクターに関するクラス
* 爆弾に関するクラス
* 爆発に関するクラス
* 敵に関するクラス
* スコアに関するクラス

### 担当追加機能
* タイトル
* 剣を振る（担当：三反田）：左shiftを押した際に、こうかとんが剣を振るクラス
* HPゲージ
* ビーム制限付き
* 新手の敵
### ToDo
### メモ
* クラス内の変数は，すべて，「get_変数名」という名前のメソッドを介してアクセスするように設計してある
* すべてのクラスに関係する関数は，クラスの外で定義してある
