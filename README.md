# ICEPP-CERN 夏の学校 2022 講義「機械学習」の補助資料
ICEPP-CERN 夏の学校 2022 講義「機械学習」の資料作成のために用いたPythonスクリプトです。
それぞれのトピックごとにJupyter notebookとしてまとめています。
scikit-learnを主に用いており、機械学習アルゴリズムの自体の実装はしていません。

## スライド
- [2022](https://drive.google.com/file/d/1-PYq3lpSYl5JblePFCcZHjxRadZUHeNo)

## 環境構築
Python3が使える場合は以下のようにして必要なパッケージをインストールできます。
```bash
python3 -m venv env
source env/bin/activate
pip install --upgrade pip
pip install -r requirements.txt

jupyter notebook
```

手元にPythonを使える環境がない場合は、[Google Colaboratory](https://colab.research.google.com/)等オンラインの環境も活用ください。

