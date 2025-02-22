# LP_template

## このLPはスワイプ型のLPを簡単に作れるものです。

## 画像設定の場合

1.	背景画像 (backgroundImage)
	•	設定されていれば、スライドの背景に適用
2.	sections/ 内のHTMLはそのまま使用可能
	•	画像は config.json で管理できるので、HTMLを直接編集しなくてもOK

例)
```config.json
{
    "siteTitle": "カスタムLP",
    "headerTitle": "ようこそ！",
    "footerText": "© 2025 すべての権利予約",
    "sections": [
        {
            "htmlFile": "sections/section1.html",
            "backgroundImage": "images/bg1.jpg"
        },
        {
            "htmlFile": "sections/section2.html",
            "backgroundImage": "images/bg2.jpg"
        },
        {
            "htmlFile": "sections/section3.html",
        }
    ]
}
```

## Formのボタンの色の変更

```css
.floating-form button {
    background: #FF4500;
}
```

## Formの設定
1.	Formspree.io に登録（無料プランでOK）
2.	フォームの ID (YOUR_FORM_ID) を設定

## UGCの追加
例えば、以下のサイトなど登録しiframeなどを追加することで実現できます。

https://embedsocial.jp/