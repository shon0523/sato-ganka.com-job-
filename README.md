# 佐藤眼科グループ 採用サイト ワイヤーフレーム（v1）

B案（医師向け情報を含む統合型採用サイト）・PC 1440px・全6ページの高精度ワイヤーフレーム。

## 見る

`Index.dc.html` をブラウザで開く（ローカルサーバー推奨：`npx serve .` など）。
各ページは 1440px の本体 ＋ 右側 320px の設計メモ（余白・意図・要確認）で構成。

## ファイル

| ファイル | 内容 |
| --- | --- |
| `Index.dc.html` | コンセプト / トーン&UI方針 / ページ一覧 / 要確認一覧 / 撮影リスト |
| `Recruit Top.dc.html` | ① RECRUIT TOP |
| `About.dc.html` | ② ABOUT｜佐藤眼科について |
| `Job.dc.html` | ③ JOB｜仕事を知る（職種タブ切替） |
| `Environment.dc.html` | ④ ENVIRONMENT｜働く環境を知る |
| `Recruit Info.dc.html` | ⑤ RECRUIT INFO｜募集要項（職種タブ切替） |
| `Entry.dc.html` | ⑥ ENTRY |
| `RecruitHeader.dc.html` / `RecruitFooter.dc.html` | 共通ヘッダー / ENTRY CTA＋フッター |
| `support.js` | 描画ランタイム（編集不要） |

## メモ

- 数値・募集条件は現行HP（採用情報 / 当グループについて / 診療実績 / 機器紹介）から転記。
- 未確認情報は「要確認」タグ、仮文言は「仮コピー」タグを付与。一覧は `Index.dc.html` 参照。
- 写真は必要カットを記載したプレースホルダー。
- JOB / RECRUIT INFO は URL ハッシュ（`#doctor` `#ort` `#nurse` `#clerk` `#other`）でタブを直接開ける。

## デザイントークン

- 和文 Zen Kaku Gothic New / 英字・数字 DM Sans（Google Fonts）
- 背景 `#FBFBFC` / 面 `#F2F4F8` / アクセント `#2A4E8F` / 文字 `#1F2433` / 募集中 `#2A7A5A` / 要確認 `#FBF3E2`
- コンテンツ幅 1160px / セクション上下 120px / カード間 24px / 角丸 12px
