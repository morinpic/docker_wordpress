FROM wordpress:latest

# パッケージのリストをサーバーから入手する
RUN apt-get update

# Wordmoveに必要なパッケージのインストール
RUN apt-get install -y ruby ssh vim mysql-client rsync

# Wordmoveインストール
RUN gem install wordmove -v 2.0.0
