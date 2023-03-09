# 予定調整くん（開発用）
GitHub 認証を利用して予定を調整してくれるアプリケシーション
```
ERROR: Volume schedule-arranger-data declared as external, but could not be found. Please create the volume manually using `docker volume create --name=schedule-arranger-data` and try again.
```
といったエラーが出た場合には以下のコマンドを実行して、再度 Docker を起動してください。
```
docker volume create --name=schedule-arranger-data
```
