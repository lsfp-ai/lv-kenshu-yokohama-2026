# 企業型DC「forche」レベルアップ研修 2026 横浜｜資料ハブ

2026年6月5日(金)–6日(土)・横浜会場の研修タイムテーブル＆資料ナビ。

公開ページ（GitHub Pages）: https://lsfp-ai.github.io/lv-kenshu-yokohama-2026/

## 方針（重要）

- このリポジトリ／公開ページには **個人情報・社外秘PDFを置きません**。
- 各PDFは **参加者限定の Google ドライブ共有** に置き、ハブからリンクします。
- ハブは「タイムテーブルの見た目」のみを公開し、リンク先のPDFは参加者のみ閲覧できます。

## 資料リンクの差し込み方

`index.html` 末尾の `const DRIVE = { ... }` に、各PDFの Google ドライブ共有URLを貼るだけです。
空欄のままだと該当資料は「（準備中）」と表示され、クリックできません。

```js
const DRIVE = {
  program:  "https://drive.google.com/...",  // 研修プログラム（全体）
  keiei:    "https://drive.google.com/...",  // 経営者に会うためには
  roleplay: "https://drive.google.com/...",  // ロープレ用資料データ
  matching: "https://drive.google.com/...",  // マッチング拠出加入者掛金の取り扱い
  kyuyo:    "https://drive.google.com/...",  // 給与ソフトの仕様変更等
  ryui:     "https://drive.google.com/...",  // 選択制DC導入に関する留意事項
  kiyaku:   "https://drive.google.com/...",  // クロス・ヘッド企業型年金規約
  meibo:    "https://drive.google.com/..."   // 懇親会参加者名簿
};
```
