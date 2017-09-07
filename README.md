# python-sandbox
## setup

```sh
# python3 -m venv env
source env/bin/activate
```

```sh
pip install -r requirements.txt
```

## init repository

リポジトリ初期化時のコマンド

```sh
source env/bin/activate
pip install flake8 # linter
pip install mypy # type analysis
pip install yapf # code formatter
pip freeze > requirements.txt
```
