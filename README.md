# ITF-Dic [![CircleCI](https://circleci.com/gh/nandenjin/itfdic.svg?style=svg)](https://circleci.com/gh/nandenjin/itfdic)
## 筑波大学生 自然言語解析辞書

MeCabで利用できる、筑波大学の独自語を自然言語解析辞書にまとめたものです。

## Build

構築済み辞書ファイルはbuildディレクトリ内に同梱されています。

手動ビルドは以下の方法で行えます（Mac OS Xの場合）。

```shell
# 
# MeCab導入により /usr/local/libexec/mecab/mecab-dict-indexが利用可能になっている必要があります。
# 

./build.sh
```

他環境でのビルドコードの提供もお待ちしています。

## Contribution

`dev`へのコミットをお願いします。コミットにはビルド済みデータを含めないようにしてください。
