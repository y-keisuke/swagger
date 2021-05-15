# swagger

swaggerを使用したAPIリファレンス

## 使用方法
1. リポジトリをcloneする。
2. コマンド　`docker compose up -d`　を実行する。
3. localhost:8081でswagger-editorが、localhost:8082でswagger-uiが起動することを確認する。
4. swagger-editorでfileを編集する。
5. 編集したファイル内容を`reference.yaml`に記載する。
6. swagger-uiで`reference.yaml`に記載した内容が表示される。
7. 4と6を繰り返す。