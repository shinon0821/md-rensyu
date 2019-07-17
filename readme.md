# 見出し1

見出し1
===

パラグラフ=段落=pタグ
改行=brタグ=半角スペース2つ以上

hello.
hello. hello. hello. hello.
hello. hello. hello. hello.
hello. hello. hello. hello.
hello. hello. hello. hello.
hello. hello. hello. hello.

> hello. hello. hello. hello. hello. hello. hello. hello.

## 区切り線

---
- ハイフン3つ

___
- アンダースコア3つ

***
- アスタリスク3つ

- - -
- ハイフンスペース3つ

## 見出し2

### 見出し3

- item1
- item2
- item3


# 　強調
hello. hello.
*hello. hello.*
hello. hello.
_hello. hello._
hello. hello.
**hello. hello.**
hello. hello.
__hello. hello.__
hello. hello.

*日本語は斜体にならないことが多い*

#ナンバリング

1. item1
1. item2
1. item3
1. item4

# ハイパーリンク

- https://www.youtube.com/
- [ドットインストール](https://dotinstall.com/)
- [ドットインストール](https://dotinstall.com "動画学習サイト")
- [md-rensyu](https://github.com/shinon0821/md-rensyu#md-rensyu)
- 作成したGitHubのマークダウンの見出しにカーソルを合わせて、左のリンクアイコンを右クリックして、 **リンクのコピー**で、その項目を直接開くリンクが得られる

# コード

- バッククォートは、[Shift]+[@]キー
- バッククォートは、言語を指定できる
　　- csならC#
    -cならc言語
```cs
function x(){
  Debug.Log("Hello.");
}
```

- インラインは、バッククォート1つで囲う。`Debug.Log()`はデバッグ表示

# 画像

![画像](kouhaku_manju.png  "from いらすとや")

[![画像](kouhaku_manju.png "from いらすとや")](https://www.irasutoya.com/2014/04/blog-post_3555.html)

|列見出し1|列見出し2|列見出し3|
|:---|:---:|---:|
|左揃え|中央揃え|右揃え|
|0|data|data|

- 1行目が行見出し
- 2行目に、列の揃えを指定。:とハイフン1つ以上
  - :--- 左揃え(:か-のみでも左揃え)
  - :---: 中央揃え
  - ---: 右揃え
- 3行目以下が、データ行
