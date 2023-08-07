---
title: CMS機能（テンプレート）について
---
HR Deliでは、ページのレイアウトをHTML形式で記述する必要があります。
テーブルやリストなどのよく利用されるHTMLについては、テンプレート一覧から追加することができます。

### 配置に関する留意点
トップページブロックとLP経由会員登録のみ、表示エリアの背景色の変更に対応するため、
テキストや画像をページの中央に配置する設定を撤廃しています。

※背景色を変更している例：トップページブロック「選ばれる理由」がございます。
![選ばれる理由のイメージ](https://e2info.github.io/hrdeli-docs/manual/img/cms_01.png)

もし他のコンテンツと同様に中央に調整したい場合は、以下のようにを```<div class="container">```挟むように設置してください。

```
<div class="container">
    <p>ここにテキストを入力</p>
</div>
```

## テンプレート一覧

No. | テンプレート名 | 表示イメージ
------------- | ------------- | ------------- |  
1 | 見出し1 | ![見出し1のイメージ](https://e2info.github.io/hrdeli-docs/manual/img/template_01.png)
2 | 見出し2 | ![見出し2のイメージ](https://e2info.github.io/hrdeli-docs/manual/img/template_02.png)
3 | リスト | ![リストのイメージ](https://e2info.github.io/hrdeli-docs/manual/img/template_03.png)
4 | テキスト（左寄せ） | ![テキスト（左寄せ）のイメージ](https://e2info.github.io/hrdeli-docs/manual/img/template_04.png)
5 | テキスト（中央寄せ） | ![テキスト（中央寄せ）](https://e2info.github.io/hrdeli-docs/manual/img/template_05.png)
6 | テキスト（右寄せ） | ![テキスト（右寄せ）のイメージ](https://e2info.github.io/hrdeli-docs/manual/img/template_06.png)
7 | テキスト＋画像 | ![テキスト＋画像のイメージ](https://e2info.github.io/hrdeli-docs/manual/img/template_07.png)
8 | 画像横並び3列 | ![画像横並び3列のイメージ](https://e2info.github.io/hrdeli-docs/manual/img/template_08.png)
9 | テーブル | ![テーブルのイメージ](https://e2info.github.io/hrdeli-docs/manual/img/template_09.png)
10 | 横フロー図（縦書き） | ![横フロー図（縦書き）のイメージ](https://e2info.github.io/hrdeli-docs/manual/img/template_10.png)
11 | 横フロー図（横書き） | ![横フロー図（横書き）のイメージ](https://e2info.github.io/hrdeli-docs/manual/img/template_11.png)
12 | 縦フロー図（横書き） | ![縦フロー図（横書き）のイメージ](https://e2info.github.io/hrdeli-docs/manual/img/template_12.png)
13 | 見出し＋画像 | ![見出し＋画像のイメージ](https://e2info.github.io/hrdeli-docs/manual/img/template_13.png)
14 | Q＆A | ![Q＆Aのイメージ](https://e2info.github.io/hrdeli-docs/manual/img/template_14.png)


[← 戻る](https://e2info.github.io/hrdeli-docs/)


{% include footer.md %}
