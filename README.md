# git-memo

## gitのcommitユーザーを強制変更する方法

1. 以下のコマンドでコミット履歴を変更
```
git commit --amend --author="New Author Name <email@address.com>"
```

ユーザーは以下で確認可能
```
git config user.name
git config user.emal
```

2. 対象のブランチにプッシュ
```
git push origin +main
```
