# docker-code-server

ARM64で使う場合は`image: ghcr.io/minetaro12/code-server:arm64-latest`に変更してください。

## 使い方

1. `mkdir ./coder`でディレクトリを作成してください。

2. `docker-compose.yml`の`user`はホスト側のuid,gidに変更してください。

3. `docker compose up -d`で起動します。
