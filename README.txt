4,320N｜ブラウザで動く2Dお世話ゲーム prototype

使い方
1. このフォルダをGitHub Pagesのリポジトリ直下に置きます。
2. index.html を開くと動作します。
3. public/assets/characters/ 以下にキャラクター画像を置いてあります。
4. 本調査用にする場合は、index.html 上部の以下を変更してください。
   const DEV_MODE = false;
   const SURVEY_URL = "実際のGoogleフォームURL";

画像について
- いただいた画像を public/assets/characters/ 以下に配置しました。
- kangaroo_blue の happy.png は、現時点では sad.png を仮コピーしています。
- rabbit_pink の happy/sad/sleep.png は、現時点では pink_sleep.png を仮コピーしています。
- 差し替える場合は、同名ファイルを上書きしてください。

ログについて
- ログはlocalStorageに保存されます。
- DEV_MODE=true のとき、画面下部からCSV/JSONでダウンロードできます。
- Googleフォームへは research_id / condition_id / character_id / language をURLパラメータで渡します。
