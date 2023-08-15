# web-sample1
1.Docker Desktopを立ち上げ
2.$ docker compose up -d  を入力

## 起こり得るエラーの解消法
1.8080のポートが既に他のプログラムに使用されている
$ sudo lsof -i -P | grep "LISTEN"
で、localhostのポートの使用を確認する。
大体これでわかる

2.わからん

