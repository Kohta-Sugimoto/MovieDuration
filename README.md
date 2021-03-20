# MovieDuration

# 概要
Youtubeのチャンネルの動画時間を合計するプログラムです。  
合計する動画は、アップロード期間の指定ができます。  

Youtubeを見ていると、この人何時間配信しているんだろうと思うこともあると思います。  
そんな時に役立つプログラムです。

[参考サイト](https://qiita.com/g-k/items/7c98efe21257afac70e9)を参考にしました。

## 使用言語
言語はPythonです。



## Description
以下のコマンドでプログラム(youtubeGetMovie.py)を実行して、動画をダウンロードします。
```bash
sudo python3 youtubeDuration.py
```

## Setting
以下のコマンドでYouTube APIを使えるようにします。
```bash
sudo pip3 install google-api-python-client
```

## プログラムの編集箇所
### 10行目
Youtube Data APIの登録に関しては[参考サイト](https://qiita.com/g-k/items/7c98efe21257afac70e9)を参考にしてください。
取得したAPIキーをプログラムにコピペしてください。  
### 11行目
ChannelIDはダウンロードしたいチャンネルのものを入力してください。  
ブラウザでチャンネルのページまで飛んで、URLにChannelIDが載っています。
![URL](https://github.com/Kohta-Sugimoto/YoutubeDownload/blob/main/youtubeURL.PNG)
### 12~15行目
ダウンロードする動画のアップロード年月日を指定します。
