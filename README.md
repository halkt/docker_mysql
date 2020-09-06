# docker_mysql
docker上でmysqlを構築する。検証用に利用する

# イメージのビルド
$ docker-Compose build

# コンテナの作成
$ docker-Compose up -d

# 起動したコンテナにログイン
$ docker exec -it docker-mysql_mysql_1 bash -p

# MySQLを起動
$ mysql -u root -p
