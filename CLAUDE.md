# CLAUDE.md
 
## プロジェクト概要
 
Next.js 製のグルメ検索サイトです。ホットペッパー API を利用して、エリアやキーワードから飲食店を検索できます。
 
## 技術スタック
 
- フレームワーク: Next.js 16 (App Router)
- UI コンポーネント: shadcn/ui
- 外部 API: ホットペッパー グルメサーチ API
- パッケージマネージャー: pnpm
 
## 開発規約
 
- コンポーネントは PascalCase、関数は camelCase、ファイル名は kebab-case
- すべてのコンポーネントに TypeScript の型定義を追加する
- API コールは Next.js の Route Handlers 経由で行い、外部 API に直接アクセスしない
 
## 禁止事項
 
- ホットペッパー API キーをコードにハードコードしない（`.env` で管理する）
- API キーを含むファイルを Git にコミットしない