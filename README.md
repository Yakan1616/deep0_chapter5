# Deep Learning from Scratch - Chapter 5 Study

このリポジトリは『ゼロから作るDeep Learning』第5章の学習用コードです。

## ディレクトリ構成

- `ch05/` - 第5章の学習コード
- `code/` - Jupyter ノートブック

## セットアップ

### 1. 外部依存ディレクトリの取得

このプロジェクトは以下のディレクトリを必要とします：

```bash
# dataset と common ディレクトリを取得
git clone https://github.com/oreilly-japan/deep-learning-from-scratch.git temp
mv temp/dataset ./
mv temp/common ./
rm -r temp
```

### 2. 依存ライブラリのインストール

```bash
pip install -r requirements.txt
```

### 3. 動作確認

以下の環境で動作確認してください：

- Python 3.7+
- NumPy
- Matplotlib

## 参考

このプロジェクトは以下の書籍の学習コードをベースにしています：

- 『ゼロから作るDeep Learning』- オライリー・ジャパン
- 公式リポジトリ: https://github.com/oreilly-japan/deep-learning-from-scratch
