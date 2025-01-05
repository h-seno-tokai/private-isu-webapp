# Private ISU WebApp Performance Tuning

## ベンチマーク結果

### 初期スコア
以下はアプリケーションの初期状態でのベンチマーク結果です。

- **スコア**: 171
- **成功リクエスト数**: 568
- **失敗リクエスト数**: 22
- **エラーメッセージ**:
  - リクエストがタイムアウトしました (GET /)
  - リクエストがタイムアウトしました (POST /login)
  - リクエストがタイムアウトしました (POST /register)

---

### 最終スコア
パフォーマンス改善後の最終スコアをここに記載します。

---

## 総括
最終スコアとともに、以下の内容を記載します。

1. **改善内容の概要**:
   - どのような変更を行ったのか。
   - 変更がどのようにスコア向上に貢献したか。

2. **課題と学び**:
   - 作業中に発生した課題。
   - そこから得られた知見や学び。

3. **次のアクション**:
   - 今後の課題や追加改善案。

---

### 使用した技術・環境
- PHP
- Nginx
- MySQL
- ベンチマーカー (Go)
- Docker Compose