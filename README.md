# 投資の大学校 ホームページ

## 概要
投資の大学校のコーポレートホームページ。  
純粋なHTML/CSS/JavaScriptで構築。フレームワーク・ビルドツールは使用していない。

## 公開URL
https://toshimitsuohuchi.github.io/toudai-web/

## 技術構成
| 項目 | 内容 |
|------|------|
| 言語 | HTML / CSS / JavaScript |
| ホスティング | GitHub Pages |
| ブランチ | main（mainへのpushで自動反映） |
| カスタムドメイン | 未設定（2026年4月時点） |

## ファイル構成
toudai-web/
├── index.html        # メインページ
├── images/           # 画像素材
│   └── instagram/    # Instagram用画像
└── .gitignore        # Git除外設定

## ローカル開発環境のセットアップ
1. このリポジトリをクローンする
```bash
git clone https://github.com/ToshimitsuOhuchi/toudai-web.git
cd toudai-web
```
2. `index.html` をブラウザで直接開く（ビルド不要）

## 更新・デプロイの手順
```bash
# ファイルを編集後
git add .
git commit -m "変更内容の説明"
git push origin main
# → GitHub Pagesに自動反映（反映まで数分かかる場合あり）
```

## 管理情報
| 項目 | 内容 |
|------|------|
| GitHubリポジトリ | https://github.com/ToshimitsuOhuchi/toudai-web |
| GitHub Pagesの設定 | リポジトリ Settings > Pages で確認 |
| 担当役員 | 大内俊光 |
| 最終確認日 | 2026年4月12日 |

## 引き継ぎ時の注意事項
- `.env`等の機密情報はリポジトリに含まれていない
- APIキー・認証情報は現時点で使用していない
- デザインガイドライン・ロゴ素材は `~/Desktop/投資の大学校/` にある
- カスタムドメイン設定時はDNS変更が必要（他役員への事前共有を推奨）
