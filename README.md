# V3MML ドキュメント

本リポジトリは、**V3MML（mac用アプリ）** に関する  
公式／準公式ドキュメントを管理・公開するためのものです。

- Web 版（Markdown / GitHub Pages）
- PDF 版
- 将来の改訂・校正履歴

を一元的に管理することを目的としています。

---

## 📘 ドキュメント一覧

### Web 版
- Markdown 版
  - [Ｖ３ＭＭＬ説明書](docs/index.md)
- html 版  
  - (html版リンク)<!-- https://＜ユーザー名＞.github.io/＜リポジトリ名＞/ -->

※ Web 版は内容確認・校正・検索性向上を目的とした補助資料です。

---

### PDF 版
- **V3MML Instruction Manual**
  - Version: **1.28**
  - ファイル:  
    - [`pdf/v3mml_inst_v128.pdf`](pdf/v3mml_inst_v128.pdf)

※ PDF は「確定版ドキュメント」として扱います。

---

## 🧾 バージョン管理方針

- **PDF**
  - バージョンごとにファイル名を固定  
    例：`v3mml_inst_v128.pdf`
  - 更新時は新しいファイルを追加
  - Git タグおよび GitHub Releases を併用

- **Markdown（Web 版）**
  - PDF 原文を基準として作成
  - 誤字脱字修正・構造整理は随時反映
  - 差分管理を重視

---

## 🛠 リポジトリ構成（概要）

```
/
README.md … 本ファイル（入口）
LICENSE … 利用条件
pdf/ … PDF 配布物
docs/ … Web 版（Markdown）
tools/ … 変換・補助スクリプト
```

---

## 🔄 更新履歴の扱い

- 大きな改訂：
  - PDF 更新
  - Git タグ + Release 作成
- 軽微な修正（誤字脱字等）：  
  - Markdown 側で履歴管理
  - 必要に応じて次回 PDF に反映

---

## 📄 ライセンス

本ドキュメントの利用条件については、  
リポジトリ内の [`LICENSE`](LICENSE) を参照してください。

