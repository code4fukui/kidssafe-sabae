# キッズセーフ 鯖江 / KidsSafe for Sabae

- https://code4fukui.github.io/kidssafe-sabae/

- 鯖江市の地域安全マップを作成して、スマホやPCで共有するツールです。
- ExcelやNumbersを使ってCSVデータを編集しアップロードすることで更新できます。
- [キッズセーフ by Code for FUKUI](https://github.com/code4fukui/kidssafe/) を使って作られています。

## サイトをホーム画面に追加する方法

- スマホの操作が苦手な方にも、すぐにキッズセーフが閲覧できるようにわかりやすい説明を作りました。
- [ホーム画面登録(android）.pptx](https://github.com/code4fukui/kidssafe-okamoto/files/14518682/android.pptx)
- [ホーム画面登録(iphone).pptx](https://github.com/code4fukui/kidssafe-okamoto/files/14518806/iphone.pptx)

## サイトの表示を外国語に切り替える方法

- サイトの表示を外国語に切り替えて表示したい場合の設定方法を解説しています。
- [外国語変換方法(iphone).pptx](https://github.com/code4fukui/kidssafe-okamoto/files/14518975/iphone.pptx)

## データの更新方法

1. 変更したいデータを確認する (例、[aed.csv](aed.csv))
2. ダウンロードボタンを押し、ダウンロードする
3. Excelで編集する
4. 位置情報は、「[緯度経度地図](https://fukuno.jig.jp/app/map/latlng/#%E8%B6%8A%E5%89%8D%E5%B8%82)」から該当場所に動かして、Geo3x3欄に表示された文字列を項目Geo3x3にコピーする
5. Excelで保存する
6. [./](./) に編集したファイルをドロップし、アップロード(Upload)する
7. 1分ほど待つと更新される

## データ種の追加方法

1. [template.csv](template.csv)をダウンロードし、Excelで開く
2. 2行目以降に地図に設定したい情報を記述する（項目は自由に増やせます）
3. Excelで保存し、データ種類がわかるような英数ファイル名で保存する
4. [index.csv](index.csv)をダウンロードし、Excelで開く
5. 3で保存したファイル名とデータ種類名、アイコンファイル名を記述する
6. [./](./) に index.csv と 3で保存したファイルをアップロードする
7. 1分ほど待つと更新される

## アイコン追加方法

1. 大きさ100x100程度の画像を用意し、PNG形式、半角英数名で保存する
2. [icon](icon)フォルダにアップロードする
3. [index.csv](index.csv)や各データをダウンロードし、icon項目を該当ファイル名に変更する
4. 編集したファイルを [./](./) へアップロードする
5. 1分ほど待つと更新される

## 要望など

- この地区のキッズセーフについて [Issues](../../issues)
- キッズセーフのアプリについて [キッズセーフのIssues](https://github.com/code4fukui/kidssafe/issues)