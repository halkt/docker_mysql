#使うDockerイメージ
FROM mysql:5.7

#ポートを開ける
EXPOSE 3306

#MySQL設定ファイルをイメージ内にコピー
ADD ./mysql.cnf /etc/mysql/conf.d/mysql.cnf

#docker runに実行される
CMD ["mysqld"]