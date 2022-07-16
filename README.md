# minecraft-server-container

## コンテナ起動
```console
root@host:/# docker compose up -d
```
## コンテナにアタッチ
```console
root@host:/# docker attach papermc
```
## 手動バックアップ
```console
root@host:/# docker compose exec mc-backup backup now
```