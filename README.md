# data-url

ファイルをData URLに変換するシェルスクリプト

## インストール

`data-url`コマンドをPATHの通ったディレクトリにコピーして実行権を付与する

## 使い方

```
data-url <file path> [format=p]

$ data-url example.jpg
# example.jpg というファイルをData URLに変換して標準出力に出力する

$ data-url example.jpg c
# example.jpg というファイルをCSSの `background-image` の値として指定できる形式で標準出力に出力する
```

## format について

| value | 説明 |
| --- | --- |
| p | そのまま出力する(デフォルト) |
| c | CSSに使えるURLとして出力する |

