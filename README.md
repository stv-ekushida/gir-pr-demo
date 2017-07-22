DevelopからMasterへPRを出す

## インストール
```
sudo gem install git-pr-release
```

## 初期設定
```
git config --file .git-pr-release  pr-release.branch.staging develop
```

## 実行
```
git-pr-release

// ユーザ名とパスワードを入力
username: <Githubのユーザ名> 
password: <パスワード>
```

## 実行結果の例

```
To be released: #1 PR1
To be released: #2 PR2
```
