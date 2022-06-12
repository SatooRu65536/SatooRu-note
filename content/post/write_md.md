---
title: "マークダウンの書き方"
date: 2022-06-12T17:33:14+09:00
author: "nagi"
tags: [other]
---


### マークダウンの書き方

#### 初めに
このブログを書くためにマークダウンの記法を一覧にしました

<!--more-->

### 段落
```Markdown
これは段落だよ[ ][ ]
改行するには空白を入れる
```

<br>

---
### 見出し
```Markdown
# 見出し h1
## 見出し h2
...
###### 見出し h6
```

<br>

---
### 強調
```Markdown
*イタリック体*
**Bold体**
***イタリック&Bold体***
~~打ち消し線~~
```

<br>

---
### リンク
#### 自動リンク
```Markdown
<http://example.com>
```


#### インラインリンク
```Markdown
[hoge](http://example.com)
[hoge](http://example.com "タイトル")
```

<br>

---
### 
```Markdown
![画像](image/hoge.png)
![画像](image/hoge.png "タイトル")
```
<br>

---
### リスト
```Markdown
* リスト1
* リスト2

1. リスト 1
    1. リスト 1-1
2. リスト 2
3. リスト 3
    1. リスト 3-1
    2. リスト 3-2
```

<br>

---
### チェックボックス
```Markdown
- [ ] チェックボックス
- [x] チェックボックス
```

<br>

---
### コード
#### コードブロック
```Markdown
 ` ` `js
 let hoge = 123
 ` ` `
```

#### インラインコード
```Markdown
 `pip install hoge` or `pip3 install hoge`
```

<br>

---
### 引用
```Markdown
> 引用
>> 入れ子引用
```

<br>

---
### 水平線
```Markdown
---
***
```

---
### テーブル
```Markdown
| Left align | Right align | Center align |
|:-----------|------------:|:------------:|
| This       |        This |     This     |
| column     |      column |    column    |
| will       |        will |     will     |
| be         |          be |      be      |
| left       |       right |    center    |
| aligned    |     aligned |   aligned    |
```