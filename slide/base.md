---
marp: true
paginate: true
theme: test
header: "**Marpではじめるスライド作成**"
footer: "Marp Sample Presentation"
---

<!--
_class: title 
-->

# タイトル

## Marp で作成するスライド資料

### 所属：〇〇

### 〇〇 〇〇

---

## Marpとは

- Markdown でプレゼンテーションスライドを作成することができるツール
- 組み込みテーマや CSS テーマによるデザインを適用して、HTML, PDF, PowerPoint などの各種形式でエクスポートすることができる

---

## 記法1

- スライドの区切りは `---` 。

```Markdown
---
marp: true
---

# タイトル

---

## スライド1枚目

    ・
    ・
    ・
```

---

## 記法2

### 見出しの一部を**青色のアクセントカラー**にする

- 見出し内で**に囲まれた部分は青色のアクセントカラーになります

### 画像

![w150](https://placehold.jp/150x150.png)

---

## コードブロック

```Java
public class test {
    public static void main(String[] args){
        // 
        System.out.println("Hello, world!");
    }
}
```

---

## 画像を入れる(右側)

![bg right:45%](https://placehold.jp/150x200.png)

---

<!--
_backgroundColor: magenta
_color: white
-->

## 結論

- 背景色マゼンタ

---

## ご清聴ありがとうございました
