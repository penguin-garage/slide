# Penguin Slide Template

Marpを使用したプレゼンテーションスライドのテンプレートです。

## 使い方

1. このテンプレートを使用するには、以下の依存関係が必要です：
   - [Bun](https://bun.sh/)

2. インストール：
   ```bash
   bun install
   ```

3. スライドの作成：
   - `slide/penguin-slide-template.md`をコピーして新しいスライドを作成
   - マークダウン形式でスライドを編集

4. スライドクラス：
   - `title`: 表紙スライド用
   - `section`: セクションタイトル用
   - `slide`: 通常のスライド用

5. スライドのプレビュー：
   ```bash
   # Marpプレビューモード
   bun preview

   # HTMLサーバーモード
   bun serve

   # HTMLサーバー + Cloudflare Tunnel
   bun start
   ```

6. スライドのビルド：
   ```bash
   # PDF出力
   bun build

   # PowerPoint出力
   bun build:pptx
   ```

## カスタマイズ

テーマのカスタマイズは`themes/marp-penguin-slide.css`で行えます。

## ライセンス

MIT License
