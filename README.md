
# クィックスタート: Compose と WordPress を Podman Desktopで動かす
https://docs.docker.jp/compose/wordpress.html 


## 起動
```
$ podman compose up -d
```

## アクセス
```
http://localhost:8000/
```

# 停止
```
$ podman copose down
```

# コンテナとデフォルトネットワーク、さらに WordPress データベースも削除
```
podman compose down --volumes
```