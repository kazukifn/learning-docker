# learning-docker: Dockerの練習

## ミニレポート

### Q1-1: 同じ `docker container run` コマンドを2回実行すると、1回目と2回目で違いはありますか？どう違いますか？

【回答欄】特に違いはなかった

### Q1-2: なぜ違いますか？

【回答欄】違いは感じられなかったので特になし

### Q1-3: `docker container ls` と `docker container ls -a` はどう違いますか？

【回答欄】-aは全てという意味になる。よって`docker container ls`は決められたもの今回は起動しているものだけ表示、`docker container ls -a`は全て表示ということになる

### Q1-4: `docker image ls` と `docker container ls -a` はどう違いますか？（間違ってもいいので、自分の考えを述べてください）

【回答欄】　`docker container ls -a`は起動ログ、`docker image ls`は起動するためのファイル、imageを作成した日時のログ

### Q1-5: `ubuntu` イメージでの `cat /etc/issue` の結果をペーストしてください

【回答欄】Ubuntu 18.04.3 LTS \n \l

### Q1-6: `docker image ls` と `docker container ls -a` はどう変化しましたか？

【回答欄】`docker image ls`は何も変わらなかったが`docker container ls -a`はログが増えていた

### Q2-1: `-d` (デタッチド・モード) でコンテナを起動すると、どのような状態になりましたか？

【回答欄】まるでコンテナが起動していないように見える。ターミナルでは仮想端末に入っていない

### Q2-2: http://localhost/ をブラウザで開くと、何が表示されましたか？

【回答欄】　Welcome to nginx!

### Q2-3: コンテナの起動時と終了時で、docker container ls -a はどのように変化しましたか？

【回答欄】  nginxの欄ができた

### Q3-1: `docker build -t sample-image .` 実行時に表示されている `building...` は、Dockerfileのどの行から実行されましたか？

【回答欄】RUN echo "building..."から実行されている

### Q3-2: `docker run sample-image` を実行すると、どうなりましたか？

【回答欄】Hello, from Docker container!が表示された

