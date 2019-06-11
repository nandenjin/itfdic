# ITF-Dic [![CircleCI](https://circleci.com/gh/nandenjin/itfdic.svg?style=shield)](https://circleci.com/gh/nandenjin/itfdic)
## 筑波大学生 自然言語解析辞書

MeCabで利用できる、筑波大学の独自語を自然言語解析辞書にまとめたものです。

## Build

構築済み辞書ファイルはbuildディレクトリ内に同梱されています。masterブランチへのコミットは自動ビルドで常に最新版に取り込まれています。

手動ビルドは以下の方法で行えます（Mac OS Xの場合）。

```shell
# 
# MeCab導入により mecab-dict-indexが利用可能になっている必要があります。
# -d オプションの引数はシステム辞書へのパスです。
# 

/usr/lib/mecab/mecab-dict-index \
-d /usr/share/mecab/dic/ipadic \
-u build/itfdic.dic \
-f utf-8 \
-t utf-8 src/itfdic.csv
```

他環境でのビルドコードの提供もお待ちしています。

## Contribution

`dev`へのコミットをお願いします。コミットにはビルド済みデータを含めないようにしてください。
