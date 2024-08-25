# Premiere-Yukkuri-Maker

**現在開発中です。ある程度完成したらReleaseからダウンロードできるようにします**

-----------

ドラッグアンドドロップだけで音声の配置・タイトルの挿入が出来るようになるエクステンションです。

また、AquesTalk Playerを使用することで、音声の作成・配置・挿入をPremiere Pro内で完結させることが出来ます。

但し、AquesTalkのライセンスに従ってご利用ください。

また、現時点ではWindowsでしか動かないと思われます。(改行コードをでCR+LF処理しているため)

## 注意

.mogrtファイルには、After Effectsで作成されたmogrtを使用する必要があります。

また、モーショングラフィックステンプレートでの書き出し時、ソーステキストは一番上に配置してください。

After Effectsを使用できない場合、私が作ったmogrtをダウンロードできるので、そちらをご利用ください。

## メモ
```
.
├── CSXS
│   └── manifest.xml
├── css
│   ├── boilerplate.css
│   ├── styles.css
│   ├── styles.css.map
│   ├── styles.scss
│   └── topcoat-desktop-dark.min.css
├── icons
│   ├── iconDarkNormal.png
│   ├── iconDarkRollover.png
│   ├── iconDisabled.png
│   ├── iconNormal.png
│   └── iconRollover.png
├── index.html
├── js
│   ├── libs
│   │   ├── CSInterface.js
│   │   └── jquery-2.0.2.min.js
│   ├── main.js
│   └── themeManager.js
└── jsx
    └── hostscript.jsx

7 directories, 17 files

```

jsxフォルダにはExtendScript

main.jsにはhtmlから呼び出されるJS

styles.scssにはCSSを書く。→styles.cssにコンパイル

ExtendScriptの呼び出しは`index.html`→`main.js`→`hostscript.jsx`→んでPremiere Proに行くという流れ
