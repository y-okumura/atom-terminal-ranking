atom-terminal-ranking
=====================

terminal系のatomプラグインで今一番人気なのが何か見てみた

1. `apm search`の結果をjsonで出力　
```sh
apm search terminal --json > terminal.json
```
1. jupyter notebook をdockerから起動
```sh
./startjupyter.sh
```
1. `http://(4ff5857fb9ca or 127.0.0.1):8888/?token=3b6477fa68c81da5c9c0c3688aedbee20604e949a41cdcd2`  
みたいな(4ff...は任意のハッシュ)リンクが表示されるので、(...)をlocalhostに置換えてアクセス
1. [ranking.ipynb](http://localhost:8888/notebooks/ranking.ipynb)を開いて`Cell > Run All`

今や[platformio-ide-terminal](https://atom.io/packages/platformio-ide-terminal)が圧倒的みたいなので、

```sh
apm install platformio-ide-terminal
```
