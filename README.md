## 環境構築

1. `docker build -t analyze-song-by-bert .`で docker イメージをビルド

2. `docker run  -it --rm -v <このディレクトリへの絶対パス>:/work -p 8888:8888 analyze-song-by-bert`で jupyter lab を立ち上げ, `localhost:8888`にアクセス
