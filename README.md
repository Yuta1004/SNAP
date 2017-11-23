# 白砂寮ネットワーク自動ログインプログラム (SNAP)

寮内ネットワークでログイン状態切れる度に再ログインするのが地味に面倒なので作りました  
jikkkou.batをタスクスケジューラなどで定期実行するようにしてあげると良いかと思います

## 動作環境
- Python 3系
- Windows10にて動作確認済み

## 使用方法
- プログラム内の\~~\は実行する環境に合わせて絶対パスを入力して下さい
- **pass.txt**の**username**に寮内ネットに接続するためのユーザネーム(例:i170xx)を、**password**にパスワードを入力して下さい  
- **jikkou.bat**を使う際は、**Python.exe**の絶対パスと**ryo_auto_login.py**の絶対パスを入力して下さい  

## 注意
- **PhantomJS**が必要です  
  - Windowsの場合  
http://phantomjs.org/ からPhantomJSをダウンロードした後、Cドライブ直下にファイルを置き、ユーザ環境変数のPathにPhantomJSを追加して下さい  

- **Selenium**が必要です  
  - **pip**などでライブラリをインストールして下さい

## SNAP?
**S**hirasunaryo **N**etwotk **A**uto login **P**rogram

