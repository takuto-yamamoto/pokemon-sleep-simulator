# githooks

## How to Use

```bash
# git hooks の設定
$ git config --local core.hooksPath .githooks

# git hooks へ実行権限を与える
$ chmod -R +x .githooks/
```

## Hooks

### pre-commit

commit 時にjupyter notebook (.ipynb) からメタデータとアウトプットを自動削除します。  

事前に必要ライブラリをインストール・アップデートしてください。

```bash
pip3 install --upgrade nbconvert
```
