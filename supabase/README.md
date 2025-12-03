# Supabase周りの設定について

## 便利コマンド

```bash
# supabaseプロジェクトをリンクして初期化
supabase link --project-ref {project_id}

# ローカルDBを初期化してマイグレーションを再度実行
supabase db reset

# 新しいマイグレーションファイルを作成
supabase migration new {migration_name}

# マイグレーションをローカルに適用
supabase migration up

# マイグレーションをリモートに適用
supabase db push
```
