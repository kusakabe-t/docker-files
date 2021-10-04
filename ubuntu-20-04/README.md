# 使い方
ビルド
```terminal
$ docker build -t ubuntu20-04 . 
```

実行 (コンテナ作成済み)
```terminal
$ docker start ubuntu20-04-container 
$ docker exec -it ubuntu20-04-container /bin/bash
```

実行 (コンテナ未作成)
```terminal
$ docker run --name ubuntu20-04-container -it ubuntu20-04 /bin/bash
```
