#使うDockerイメージ
FROM mysql:5.7

#ポートを開ける
EXPOSE 3306

#MySQL設定ファイルをイメージ内にコピー
ADD ./mysql.conf /etc/mysql/conf.d/mysql.conf

#docker runに実行される
CMD ["mysqld"]