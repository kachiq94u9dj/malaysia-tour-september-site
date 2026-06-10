# マレーシアツアー 旅のしおりサイト

## プロジェクト概要

- **サイト名**: マレーシアツアー 第5回 旅のしおり
- **本番URL**: https://malaysia-tour-lake.vercel.app
- **Vercelプロジェクト**: `kachi-s-projects1/malaysia-tour`
- **GitHubリポジトリ**: https://github.com/kachiq94u9dj/malaysia-tour-september-site

## ファイル構成

```
september-deploy/
├── index.html       # サイト本体（唯一の編集対象）
└── photos/          # 過去ツアー写真（1st〜4th）
```

## 修正・デプロイのワークフロー

`index.html` を修正したら、以下をセットで実行する：

```bash
cd "/Users/imaikazuhiro/Documents/Obsidian base/10_Projects/Malaysia-Tour-2/september-deploy"

# 1. git コミット
git add index.html
git commit -m "修正内容の説明"

# 2. git push
git push origin main

# 3. Vercel 本番デプロイ
vercel --prod
```

## 関連ファイル（Obsidian vault）

- **最終プラン**: `10_Projects/Malaysia-Tour-2/03_最終プラン.md`
- **しおり（Markdown）**: `10_Projects/Malaysia-Tour-2/04_旅のしおり.md`
- **しおり（HTML）**: `10_Projects/Malaysia-Tour-2/05_旅のしおり.html`（september-deploy/index.html と同内容）

## ツアー基本情報

- **日程**: 2026年 9月26日（土）〜 28日（月）2泊3日
- **目的地**: マレーシア・クアラルンプール（KL）
- **主催**: かっちゃん（今井かづひろ）
