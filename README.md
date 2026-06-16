# Sales Analysis Project

## 概要

Python を使用して販売データの分析を行ったデータ分析学習プロジェクトです。

本プロジェクトでは、販売データをもとに、顧客ごとの購入傾向や商品別の販売状況を分析し、データの集計・可視化を行いました。

データ分析の基礎であるデータ前処理、欠損値確認、集計、可視化、分析結果の確認を学習することを目的として作成しました。

また、Jupyter Notebook を利用して、分析過程を確認しながら学習できる構成にしています。

## 使用技術

- Python
- pandas
- matplotlib
- Jupyter Notebook
- Git / GitHub

## 分析内容

- 販売データの読み込み
- データ前処理
- 欠損値確認
- 顧客別購入傾向分析
- 商品別販売数集計
- データ可視化
- グラフ作成

## 主な機能

- CSV データ読み込み
- pandas を利用したデータ集計・分析
- matplotlib を利用したグラフ表示
- 顧客ごとの購入傾向分析
- 商品別販売状況分析
- Jupyter Notebook ベースの分析環境

## 実行方法

### 1. 仮想環境作成

```bash
python -m venv venv
```

### 2. 仮想環境有効化

Mac / Linux:

```bash
source venv/bin/activate
```

Windows:

```bash
venv\Scripts\activate
```

### 3. ライブラリインストール

```bash
pip install -r requirements.txt
```

### 4. Jupyter Notebook 起動

```bash
jupyter notebook
```

## ディレクトリ構成

```text
sales-analysis-project/
├── data/
├── notebooks/
├── requirements.txt
├── README.md
└── .gitignore
```

## 学習・開発ポイント

- pandas を利用して販売データの集計と分析を行いました。
- matplotlib を利用して分析結果を可視化しました。
- 顧客ごとの購入傾向を確認できるようにデータを整理しました。
- データ前処理を通して、欠損値やデータ形式の確認を行いました。
- Jupyter Notebook を利用して、分析過程を確認しやすい構成にしました。

## 今後の改善予定

- 売上予測機能の追加
- 機械学習モデルの導入
- 顧客クラスタリング
- 分析結果のレポート化
- Streamlit を利用したダッシュボード化

## Author

GitHub: [Tatsumakiri](https://github.com/Tatsumakiri)
