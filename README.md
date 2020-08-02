# 0803
JavaScript小テスト0803

- Pure js
- jQuery
- Vue.js

上記のどれかで書いてください。

## 蝉の鳴き声

audio要素で読み込んであります。  
再生は.play()、一時停止は.pause()で

[HTMLMediaElement.play()](https://developer.mozilla.org/ja/docs/Web/API/HTMLMediaElement/play)

## Vue.jsでの要素

- console.log(this)で、$el内のオブジェクトで確認
- Vueインスタンス内でもjQueryが使えます。

## autoplay

自動再生は、ブラウザベンダーによってautoplayポリシーが違います。  
Google Chromeは、音声のautoplayを推奨していないので、設定していてもブラウザで拒否されます。  

[Google Chrome, Safari の自動再生ポリシー変更について](https://support.millvi.jp/hc/ja/articles/360034752634-Google-Chrome-Safari-%E3%81%AE%E8%87%AA%E5%8B%95%E5%86%8D%E7%94%9F%E3%83%9D%E3%83%AA%E3%82%B7%E3%83%BC%E5%A4%89%E6%9B%B4%E3%81%AB%E3%81%A4%E3%81%84%E3%81%A6)
