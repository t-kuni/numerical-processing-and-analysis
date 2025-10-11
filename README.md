# 数値の処理と数値解析

## セットアップ

### 1. 仮想環境の作成と有効化

```bash
# 仮想環境を作成
python3 -m venv venv

# 仮想環境を有効化
source venv/bin/activate
```

### 2. 依存関係のインストール

```bash
pip install -r requirements.txt
```

### パッケージを追加する

```bash
source venv/bin/activate
pip install xxx
pip freeze > requirements.txt
```

## 使用方法

### Jupyter Notebookの起動

```bash
# 仮想環境を有効化（まだの場合）
source venv/bin/activate

# Jupyter Notebookを起動
LD_LIBRARY_PATH="" jupyter notebook
```

ブラウザが自動的に開き、Jupyterのインターフェースが表示されます。

### ノートブックの実行

1. 任意の `.ipynb` ファイルをクリックして開く
2. 各セルを順番に実行する（Shift + Enter または再生ボタン）

## 仮想環境の無効化

作業が終了したら、仮想環境を無効化できます：

```bash
deactivate
```

## セルを挿入するショーロカット

Esc -> b

## セルの種類を切り替えるショートカット

* **コードセルに切り替え**: `Esc` → `y`
* **Markdownセルに切り替え**: `Esc` → `m`
* **生セル (Raw Cell) に切り替え**: `Esc` → `r`

いずれもコマンドモード（セルの枠が青い状態）で有効です。
