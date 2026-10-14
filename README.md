# Mint Writer 🌱

思いついた時にサクッと書けて、手元にシンプルに置いておける軽量・単一HTMLの執筆用テキストエディタです。  
A lightweight, single-file HTML text editor designed for quick, distraction-free creative writing.

---

## 特徴 / Features

- **完全スタンドアロン / Completely Standalone**: HTMLファイルをブラウザで開くだけで即起動。外部サーバー不要。 (Runs directly in your browser with a single HTML file. No external servers needed.)
- **階層管理 / Hierarchical Organization**: 作品・棚・話の3層構造でエピソードやプロットを整理。 (Organize your stories with Works, Shelves, and Episodes.)
- **縦書き / 横書き 切り替え / Vertical & Horizontal Writing**: ボタンひとつで原稿用紙風の縦書き表示と一般的な横書き表示をトグル。 (Easily toggle between vertical and horizontal writing modes.)
- **安心のデータ管理 / Secure Local Storage**: ブラウザ内部（LocalStorage）への自動保存 ＋ JSON形式でのバックアップ・復元に対応。 (Auto-saves locally via browser LocalStorage, with JSON export/import for backups.)
- **レスポンシブ＆全画面対応 / Mobile Friendly**: PCはもちろん、スマホのブラウザやPWA風の全画面表示にも対応。 (Optimized for both desktop and mobile devices.)

---

## 使い方 / How to Use

### 1. 起動と執筆 / Getting Started
1. `index.html`（または `mint_writer.html`）をブラウザで開きます。  
   (Open `index.html` in your web browser.)
2. 左メニューの「＋ 作品」「＋ 棚」「＋ 話」から構成を作って執筆を開始します。  
   (Create your structure using "+ Work", "+ Shelf", and "+ Episode", then start writing.)
3. `Ctrl + S`（または画面右上の 💾 ボタン）で手動保存が可能です。  
   (Use `Ctrl + S` or click the 💾 button to save manually.)

### 2. バックアップとデータ移行 / Backup & Data Migration
ブラウザのキャッシュ消去による意図しないデータ消失を防ぐため、こまめなバックアップを推奨します。  
To prevent accidental data loss from browser cache clearing, frequent backups are strongly recommended.

- **書き出し (Export)**: 左メニューの「📥 バックアップ」を押すと、日付入りの `.json` ファイルがダウンロードされます。  
  (Click "📥 Backup" in the left sidebar to download a timestamped `.json` file.)
- **復元・移行 (Import)**: 移動先の端末で Mint Writer を開き、「📤 復元」からバックアップファイルを選択すると、全データが復元されます。  
  (Open Mint Writer on your target device and select "📤 Restore" to import your `.json` backup file.)

---

## 開発方針・クレジット / Development & Credits

世の中の執筆ツールが多機能すぎて設定に疲れたため、自分用にサクッと書ける環境を目指して開発したツールです。  
コードの設計・実装・リファクタリングには、開発アシスタントとして生成AI（Gemini）を活用しています。

This is a personal hobby project created to provide a simple, stress-free writing environment.  
Generative AI (Gemini) was used as a coding assistant for the design, implementation, and optimization of this project.

- **Author**: アイス (Ice)
- **Development Partner**: Gemini

---

## 利用規約・免責事項 / Terms & Disclaimer

- 個人利用、商用利用、コードの改変・カスタマイズ、再配布はご自由にどうぞ。  
  (Free for personal use, commercial use, modification, and redistribution.)
- 自作発言はお控えください。改変して再配布する場合は、本プロジェクト（Mint Writer）をベースにしている旨を明記していただけると幸いです。  
  (Please do not claim original authorship. If redistributing modified versions, providing attribution to Mint Writer is appreciated.)
- 個人制作のフリーツールのため、不具合修正や個別サポートの保証はありません。本ツールの使用によって生じたデータの損失やトラブルについて、作者は一切の責任を負いません。大切な原稿は必ず「📥 バックアップ」機能で自己防衛をお願いします。  
  (Provided "as is" without warranty or dedicated support. The author is not responsible for any data loss or issues. Please ensure you take regular backups.)
