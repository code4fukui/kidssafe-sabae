# キッズセーフ 鯖江

- https://code4fukui.github.io/kidssafe-sabae/

鯖江市の地域安全マップを作成して、スマートフォンやPCで共有できるツールです。ExcelやNumbersで編集したCSVデータをアップロードすることで、地図の内容を更新できます。[キッズセーフ by Code for FUKUI](https://github.com/code4fukui/kidssafe/) を使って作られています。

## サイトをホーム画面に追加する方法
スマホの操作が苦手な方にも、すぐにキッズセーフが閲覧できるよう、わかりやすい説明を用意しています。
- [ホーム画面登録(Android)](https://github.com/code4fukui/kidssafe-okamoto/files/14518682/android.pptx)
- [ホーム画面登録(iPhone)](https://github.com/code4fukui/kidssafe-okamoto/files/14518806/iphone.pptx)

## サイトの表示を外国語に切り替える方法
サイトの表示を外国語に切り替える設定方法を解説しています。
- [外国語変換方法(iPhone)](https://github.com/code4fukui/kidssafe-okamoto/files/14518975/iphone.pptx)

## データの更新方法
1. 変更したいデータ(例:aed.csv)を確認する
2. ダウンロードボタンを押して、ファイルをダウンロードする
3. Excelで編集する
4. 位置情報は「[緯度経度地図](https://fukuno.jig.jp/app/map/latlng/#%E8%B6%8A%E5%89%8D%E5%B8%82)」で該当場所を確認し、Geo3x3欄の文字列をコピーする
5. Excelで保存する
6. [./](./) フォルダにファイルをアップロードする
7. 1分ほど待つと更新される

## データ種の追加方法
1. [template.csv](template.csv)をダウンロードし、Excelで開く
2. 2行目以降に地図に設定したい情報を入力する
3. ファイル名を分かりやすい英数字で保存する
4. [index.csv](index.csv)をダウンロードし、Excelで開く
5. 3で保存したファイル名とデータ種類名、アイコンファイル名を記述する
6. [./](./) フォルダにindex.csvと3で保存したファイルをアップロードする
7. 1分ほど待つと反映される

## アイコンの追加方法
1. 100x100ピクセル程度のPNG画像を用意し、半角英数字のファイル名で保存する
2. [icon](icon)フォルダにアップロードする
3. [index.csv](index.csv)や各データをダウンロードし、icon項目を更新する
4. 編集したファイルを[./](./) にアップロードする
5. 1分ほど待つと反映される

## 要望など
- この地区のキッズセーフについては[Issues](../../issues)
- キッズセーフのアプリについては[キッズセーフのIssues](https://github.com/code4fukui/kidssafe/issues)