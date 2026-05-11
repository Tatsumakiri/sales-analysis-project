# Sales Analysis Project

## 概要

このプロジェクトは、Pythonを用いて販売データを分析する個人学習プロジェクトです。  
Pandasによるデータ前処理、集計、Matplotlibによる可視化、scikit-learnによる簡易的な分類モデル作成までの一連の流れを実装しました。

ADsPで学習したデータ理解、前処理、探索的データ分析、統計的な集計、データマイニングの基礎をPythonで実践することを目的としています。

## 使用技術

- Python
- Pandas
- Matplotlib
- scikit-learn
- Jupyter Notebook

## 分析内容

- 販売データの読み込み
- データ型、欠損値、基本統計量の確認
- 売上金額カラムの作成
- 月別売上分析
- 商品別販売数量分析
- 商品別売上分析
- カテゴリ別売上分析
- 顧客別購買回数、総購入金額、平均購入金額の分析
- 再購入顧客の割合分析
- Decision Tree Classifierを用いた再購入顧客の簡易予測モデル作成

## プロジェクト構成

```text
sales-analysis-project/
├── data/
│   └── sales_data.csv
├── notebooks/
│   └── sales_analysis.ipynb
├── src/
├── README.md
├── requirements.txt
└── .gitignore