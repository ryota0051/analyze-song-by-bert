## 環境構築

1. `docker build -t analyze-song-by-bert .`で docker イメージをビルド

2. `docker run  -it --rm -v <このディレクトリへの絶対パス>:/work -p 8888:8888 analyze-song-by-bert`で jupyter lab を立ち上げ, `localhost:8888`にアクセス

## 解析内容

1. Bert によるベクトルを umap にて可視化

2. 1 で使用したベクトルで選択した曲と類似した曲を表示

3. 感情分析でアーティストごとの曲の negative, positive の分布を描画
