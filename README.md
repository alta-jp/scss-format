# scss-format

## ファイルの説明

```
style.scss
├ _base.scss          : （ヘッダ、フッタなど、全ページ共通要素）
├ _common.scss        : （mb20などの便利クラス、新規commonは別途作成してOK）
├ _contact-wpcf7.scss : （ワードプレス用のお問い合わせ系専用）
├ _contact.scss       : （お問い合わせ系専用）
├ _parts.scss         : （ページ共通の部品郡）
├ _reset.scss         : （CSSをリセットしている）
├ _top.scss           : （トップページ専用）
└ その他の下層ページ用scssを読み込む
```


## フォルダの説明

```
common_import        ： _common.scss用
contact_import       ： _contact.scss用
contact-wpcf7_import ： _contact_wpcf7.scss用
parts_import         ： _parts.scss用
```

> ※_parts.scssでは不要なデザインパーツは読み込まなくてもいい。
> ※共通要素は、パーツ化して、partsフォルダにわけていくのも良い。
