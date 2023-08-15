# web-sample1
1.Docker Desktopを立ち上げ <br>
2.$ docker compose up -d  を入力 <br>

## 起こり得るエラーの解消法
1.8080のポートが既に他のプログラムに使用されている <br>
$ sudo lsof -i -P | grep "LISTEN" <br>
で、localhostのポートの使用を確認する。 <br>
大体これでわかる <br>

2.わからん <br>

