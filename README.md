## error リスト

- docker compose 時立ち上がらなかった

▼ エラー

```
web_1              | A server is already running. Check /app/tmp/pids/server.pid.
```

▼ 解決策

```
docker-compose run --rm api rm tmp/pids/server.pid
```

# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

- Ruby version

- System dependencies

- Configuration

- Database creation

- Database initialization

- How to run the test suite

- Services (job queues, cache servers, search engines, etc.)

- Deployment instructions

- ...
