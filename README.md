# docker_mysql
docker上でmysqlを構築する。検証用に利用する

# イメージのビルド
$ docker-compose build

# コンテナの作成
$ docker-compose up -d

# 起動したコンテナにログイン
$ docker exec -it docker_mysql bash -p

# MySQLを起動
$ mysql -u root -p
