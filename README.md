# LP_template

## このLPはスワイプ型のLPを簡単に作れるものです。

## 画像設定の場合

1.	背景画像 (backgroundImage)
	•	設定されていれば、スライドの背景に適用
2.	通常画像 (image)
	•	設定されていれば、スライドのコンテンツ内に表示
3.	sections/ 内のHTMLはそのまま使用可能
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
            "backgroundImage": "images/bg1.jpg",
            "image": "images/sample1.jpg"
        },
        {
            "htmlFile": "sections/section2.html",
            "backgroundImage": "images/bg2.jpg"
        },
        {
            "htmlFile": "sections/section3.html",
            "image": "images/sample3.jpg"
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