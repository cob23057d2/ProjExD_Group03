# こうかとんサバイバー

## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
* 主人公キャラクターこうかとんをキーボードで操作して、一定時間敵から生き残るゲーム
* 参考URL：[サイトタイトル](https://www.hoge.com/)

## ゲームの遊び方
* 矢印キーでこうかとんを操作し，画面外から出現する敵を倒していくゲーム。
* こうかとんが敵にぶつかったり、爆弾に当たったりしたらゲームオーバー。

## ゲームの実装
### 共通基本機能
* 背景画像と主人公キャラクターの描画
* 敵の出現と、爆弾発射

### 分担追加機能
* 敵に追尾するビームの発射（担当：てる）
* レベルアップ機能（担当：てつま）
* ドリアンの生成（担当：てつま）
* サッカーボールの生成
* マルチビームの生成（担当：てる）
* 新しい敵を作成（敵ごとに速度を変える）（担当：はるき）
* 一定時間たったら強化アイテムをどこかに出現させる（担当：やまと）
* 何体か倒したらボスを出現（ボスの出現中は雑魚が出ない）（担当：れい）
* 重力波をアイテムで発生（担当：やまと）

### ToDo
- [X] 敵に追尾するビームの発射
- [ ] レベルアップ機能
- [ ] ドリアンの生成
- [ ] サッカーボールの生成
- [ ] マルチビームの生成
- [x] 新しい敵を作成（敵ごとに速度を変える）
- [x] 一定時間たったら強化アイテムをどこかに出現させる
- [ ] 何体か倒したらボスを出現（ボスの出現中は雑魚が出ない）
- [x] 重力波を発生

### メモ
* 特になし
