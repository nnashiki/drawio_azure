# drawio_azure
drawioでazureを使った構成図 を作る

やることは + アルファ
https://qiita.com/nassy20/items/4c19380fa6a338bd4f09

# 説明
## 図を作るってどんなとき
- 構成図
- ワークフロー
- ワイヤーフレーム
    - (ワイヤーフレームはdrawioでやったことないです。)

## なぜ drawio
- テキストでバージョン管理できる
- 継続的に構成図管理したい
   - git + diff
   - このように差分が見れる https://github.com/nnashiki/drawio_azure/pull/1#issuecomment-737051053
- oss
   - エクセルはプライベートで使えない
- svg 出力できる
- デフォルトでアイコンがある
- live share できる

## アクション
- 背景の色を変える
- アウトラインとレイヤー を用意する
- docker の検索をしてみる
- icon を import
- 背景をつくる
- 構成図作る
- export

## 注意点
- vscode integration の場合、scratchpad は使えない
  - https://github.com/hediet/vscode-drawio/issues/171

## 参考
- https://qiita.com/nassy20/items/4c19380fa6a338bd4f09
- https://github.com/hediet/vscode-drawio
- azure icon
    - https://github.com/yaegashi/icon-collection-mxlibrary/tree/mxlibrary
    - https://qiita.com/yaegashi/items/e661507765c48db09e2b
