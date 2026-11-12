# SOZIN — 創人デザインシステム株式会社

SOZIN Ballet de’ Arte のWebツール用独立リポジトリ。

## サービス
- [見積もりシミュレーター](./estimate/) — 概算価格・A4一枚PDF・軽量JPEG（**仮価格の試作版**）
- [過去バージョン](./estimate/versions/) — V0.1〜V0.4を保存

## 開発運用（Issue駆動）
1. GitHub Issueを作成し、目的・受入条件・影響範囲を記述
2. `issue/<番号>-<短い題名>` の作業ブランチを作成
3. ブランチへコミットし、PRに `Refs #番号` / `Closes #番号` を記載
4. 内容・安全性・表示を確認してマージ
5. `estimate/CHANGELOG.md` に更新履歴を記録

## 保管方針
- サービスごとに独立ディレクトリ（`estimate/`、将来 `order/`、`invoice/` など）
- 相対パスを使い、他サーバーへディレクトリごと移設可能にする
- 顧客写真、氏名、決済情報、API秘密鍵は公開GitHubへ保存しない
- Wix・メール・DNS本番設定に無断変更しない

## 公開予定
https://neyito96.github.io/sozin/estimate/

> 2026-11-12 現在、料金と機能は検証用。社長確認前の価格を正式見積として利用しない。
