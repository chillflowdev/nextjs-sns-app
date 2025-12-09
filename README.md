# SNS Message App

## 📌 概要
Next.js の Server Actions と FormData 処理を重点的に学ぶために作成したシンプルな SNS メッセージ投稿アプリです。  
投稿したメッセージは DB に保存され、リアルタイムに取得して表示します。

## 🛠️ 技術スタック
- Next.js (App Router)
- Server Components
- Server Actions (useFormState)
- FormData handling
- SQLite（または Mock DB）

## 🎯 主な機能
- メッセージ投稿フォーム（Server Action）
- DB へのメッセージ保存
- 保存済みメッセージの一覧取得・表示

## 💡 学習ポイント
- Server Action によるフォーム送信処理
- `useFormState` を使ったバリデーションや UI 更新
- Server Component でのデータ取得・表示
- FormData の取り扱いと Next.js 独自の送信フロー
