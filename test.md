# Markdownの記法
自力でMarkdownを書いてみたい意欲のある人は読んでください。

コードの書き方を教わりたい人は電気系学科に行くか、自分はいくらでも教えるので聞いてください。

環境としてはVScodeを想定しています。自分はこれでやっているのでこれ以外の環境の人は教えられないです。すみません。

## 改行
```markdown
文1__ (←_一つは一個のスペースを指します)
文2

文3
```

出力

文1  
文2

文3

## 引用

```markdown
>あいうえお
>>入れ子
```

出力

>あいうえお
>>入れ子

## 番号付きリスト

```markdown
1. リスト1
   1. リスト1-1
   2. リスト1-2
2. リスト2
```

出力

1. リスト1
   1. リスト1-1
   2. リスト1-2
2. リスト2

## リスト
```markdown
- リスト1
  - リスト1-1
- リスト2
```

出力
- リスト1
  - リスト1-1
- リスト2


## 定義
```markdown
<dl>
  <dt>オレオ</dt>
  <dd>クッキー＆クリーム</dd>
</dl>
```

出力

<dl>
  <dt>オレオ</dt>
  <dd>クッキー＆クリーム</dd>
</dl>

## インライン表示
```markdown
`int i = 0`
```

出力

`int i = 0`

## コードの挿入

```markdown
    ```c
    for(int i = 0; i < n; ++i){
        printf("%d\n", i);
    }
    ```
```

出力

```c
for(int i = 0; i < n; ++i){
    printf("%d\n", i);
}
```

## リンクの挿入
```markdown
[YouTube](https://www.youtube.com/)
```

出力

[YouTube](https://www.youtube.com/)

## 画像の挿入
```markdown
![ダミー画像](https://via.placeholder.com/150)

![ダミー画像](https://via.placeholder.com/150 "ダミー画像")
```

出力

![ダミー画像](https://via.placeholder.com/150)

![ダミー画像](https://via.placeholder.com/150 "ダミー画像")

## 打ち消し
```markdown
~~打ち消し~~
```

出力

~~打ち消し~~

## 水平線
```markdown
***

---
```

出力

***

---

## 強調
```markdown
*強調*

**強調**

***強調***
```

出力

*強調*

**強調**

***強調***


## 注釈
```markdown
aiueo[^1]
[^1]:aiueo
```

出力

aiueo[^1]

[^1]:aiueo


## 文字色の変更
```markdown
<span style="color: red">あいうえお</span>
```

出力

<span style="color: red">あいうえお</span>

[ホームに戻る](README.md)