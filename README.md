# Python学習用

## 使用しているバージョン
- Python 3.12.11

## 仮想環境の作成
[NAME]に仮想環境の名前を指定する。  
何も指定していない場合は、デフォルトで `.venv` となる
```sh
uv venv [NAME]
```

## 仮想環境の利用
[NAME]に仮想環境の名前を指定する。  
```sh
source [NAME]/bin/activate
```

仮想環境の名前を指定していない場合は、`.venv`
```sh
source .venv/bin/activate
```

## 仮想環境の終了
```
deactivate
```

## 対話型シェルを利用したPythonの実行
```
uv run python
```
または
```
python
```

## Pythonのファイルの実行
```
uv run [FILE_NAME]
```
または
```
python [FILE_NAME]
```