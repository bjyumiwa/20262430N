4,320N GitHub Pages 実装用差し替えセット

使い方
1. このZIPを解凍します。
2. index.html を GitHub の既存 index.html と置き換えます。
3. public フォルダをそのまま GitHub にアップロードします。
4. GitHub Pages を開き直します。表示が古い場合は、ブラウザで強制再読み込みをしてください。

今回変えたところ
- マカロン選択画面をCSSの仮マカロンではなく、public/assets/macarons/*.png を読む形に変更しました。
- 紫の子の happy / sad / sleep を public/assets/characters/cat_purple/ に配置しました。
- happy.png は背景のチェック模様をできるだけ透明化しました。
- キャラクター画像が読み込めないときも、動物名ではなく「✦」だけが出るようにしました。
- 誕生画面で同じキャラ画像が2回出ていた部分を1回に直しました。

画像パス
public/assets/characters/cat_purple/happy.png
public/assets/characters/cat_purple/sad.png
public/assets/characters/cat_purple/sleep.png

public/assets/macarons/pink_macaron.png
public/assets/macarons/blue_macaron.png
public/assets/macarons/yellow_macaron.png
public/assets/macarons/white_macaron.png
public/assets/macarons/green_macaron.png
public/assets/macarons/purple_macaron.png

注意
他のキャラクター画像も使う場合は、index.html内のCHARACTERSに書かれている同じ場所へ、
happy.png / sad.png / sleep.png の3枚を置いてください。
