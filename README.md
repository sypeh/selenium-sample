# selenium-sample
selenium gridの実行環境を用意するリポジトリ。
pythonでテスト用のスクリプトを書いていきます。

# 使い方
dockerを立ち上げます。
```
cd docker
docker-compose build
docker-compose up -d
```

pythonコンテナに入る
```
docker exec -it python /bin/bash
```

sampleプログラムを実行
```
cd tests/
python sample.py 
```

# selenium browserで動きを確認する
vnc://localhost:55000 にパスワード `secret` で接続し、sampleプログラムを実行
