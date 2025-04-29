# Kaggle プロジェクト環境

このリポジトリはKaggleのコンペティションやデータ分析を行うための環境を提供します。

## セットアップ方法

1. Python 3.8以上の環境を用意してください
2. 必要なパッケージをインストール:
```bash
pip install -r requirements.txt
```
3. Kaggle APIの設定:
   - Kaggleのアカウントを作成
   - APIキーを取得（https://www.kaggle.com/settings/account）
   - APIキーを`~/.kaggle/kaggle.json`に配置

## 使用方法

1. Jupyter Notebookを起動:
```bash
jupyter notebook
```

2. Kaggleデータセットのダウンロード:
```bash
kaggle competitions download -c [コンペティション名]
```

## プロジェクト構造

- `data/`: データセットを格納するディレクトリ
- `notebooks/`: Jupyter Notebookファイルを格納するディレクトリ
- `src/`: ソースコードを格納するディレクトリ 