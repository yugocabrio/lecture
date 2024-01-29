- [トランザクションのライフサイクル](#トランザクションのライフサイクル)
  - [トランザクションの伝搬](#トランザクションの伝搬)
  - [独立したトランザクションの検証](#独立したトランザクションの検証)
  - [EthereumのMempool](#ethereumのmempool)
  - [ブロックの作成](#ブロックの作成)
  - [トランザクションの実行](#トランザクションの実行)
  - [ブロックチェーンの構造](#ブロックチェーンの構造)
  - [EthereumのPoW (Proof-of-Work)](#ethereumのpow-proof-of-work)
  - [独立したブロックの検証](#独立したブロックの検証)
  - [コンセンサスとマイニング報酬](#コンセンサスとマイニング報酬)
- [まとめ](#まとめ)


# トランザクションのライフサイクル
 
Ethereumの構成要素がどのように動くのか、トランザクションのライフサイクルを軸に詳細をみてみよう。

```
EOAは、トランザクション(Message Call or Contract Creation)を各ノードに伝搬する
各ノードは、受け取ったトランザクションを独立に検証する
各ノードは、問題が無いトランザクションのみを溜め、かつ他のノードに伝搬する
マイナーノードは、溜まりから任意のトランザクションをブロックに格納する
マイナーノードは、ブロック内のトランザクションを実行する
マイナーノードは、ブロックを既存のチェーンに含まれるいずれかのブロックに繋ぐ
マイナーノードは、PoW (Proof-of-Work) を経てブロックを完成させる
マイナーノードは、完成したブロックを各ノードに伝搬する
各ノードは、受け取ったブロックに問題が無いかを独立に検証する
各ノードは、問題が無いブロックのみを自身のチェーンに反映する
Ethereumは、最も重いチェーンを「正しい」状態遷移の記録とする
```

## トランザクションの伝搬
## 独立したトランザクションの検証
## EthereumのMempool
## ブロックの作成
## トランザクションの実行
## ブロックチェーンの構造
## EthereumのPoW (Proof-of-Work)
## 独立したブロックの検証
## コンセンサスとマイニング報酬

# まとめ
- トランザクションのライフサイクルを詳細に確認した　

詳細は構造はここまで。最後にEthereumのガバナンスと課題をみてみよう。