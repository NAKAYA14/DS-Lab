FROM jupyter/datascience-notebook:x86_64-ubuntu-22.04

# 作業ディレクトリを変更
WORKDIR /home/jovyan/work

# ファイルのコピー
COPY requirements.txt ${PWD}

# pip自体のアップデート
RUN pip install -U pip

# pythonのパッケージをインストール
RUN pip install -r requirements.txt