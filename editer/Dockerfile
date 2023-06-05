FROM ubuntu:22.04

RUN apt update && \
    apt-get update

# パッケージのインストール
RUN apt-get install -y \
    fish \
    tmux

# デフォルトをfishに
RUN chsh -s /usr/bin/fish
