# clocon ブランド使用ガイド

## 基本仕様（確定）
- **ブランド名 / ハンドル**：`clocon`（クロコン）
- **書体**：Kalam（手描きブラシ体・SIL OFL 商用可）
- **シンボル**：ブラシの「c」＋右上に小さな黄ドット（案C）
- **カラー**
  - 深い紺 Navy：`#15243F`
  - 深い黄 Yellow：`#F2B100`
  - 白 White：`#FFFFFF`
- **配色ルール**
  - 紺背景：文字＝白、アクセント（! やドット）＝黄
  - 白背景：文字＝紺、アクセント＝黄（カラー版）／単色運用はモノクロ版

## ファイル一覧（`final/` 内・すべて透過PNG・2倍解像度）

### 紺背景で使う
| ファイル | 用途 |
|---|---|
| `avatar_clocon.png` (1000²) | **ココナラのプロフィール画像**・SNSアイコン |
| `symbol_navybg.png` | アプリアイコン風のシンボル（角丸紺） |
| `logo_horizontal_navybg.png` | 紺帯のヘッダー・サムネ |
| `wordmark_navybg.png` | 文字のみ（紺背景） |

### 白・明るい背景で使う（カラー）
| ファイル | 用途 |
|---|---|
| `logo_horizontal_color.png` | 資料・LP・白背景バナー |
| `symbol_color.png` | 白地のアイコン／透かし |
| `wordmark_color.png` | 文字のみ（白背景） |

### モノクロ（単色運用・印刷・スタンプ・透かし）
| ファイル | 用途 |
|---|---|
| `logo_horizontal_mono_navy.png` / `wordmark_mono_navy.png` / `symbol_mono_navy.png` | 紺一色 |
| `logo_horizontal_mono_black.png` / `wordmark_mono_black.png` / `symbol_mono_black.png` | 黒一色 |

## 使い分けの目安
- **ココナラのアイコン** → `avatar_clocon.png`
- **出品サムネ（紺背景で映えさせる）** → `logo_horizontal_navybg.png` を土台に文言を追加
- **納品資料のヘッダー/フッター（白地）** → `logo_horizontal_color.png` か `mono_navy`
- **小さく1色でだけ入れたい（透かし等）** → `symbol_mono_navy.png`

## 参考・制作データ
- `final_preview.png`：全パターンの一覧プレビュー
- `brand_sheet_v2.png`：ブランドシート
- `font_compare_navy_yellow.png` / `symbol_options.png`：検討時の比較
- `fonts/Kalam.ttf`：使用フォント本体（再制作用）
- `archive_v1/`：旧デザイン（吹き出し＋シアン版・不使用）

## 再制作・改変
ロゴは HTML＋Kalam フォントを Chromium でレンダリングして生成しています。
色や文言の差し替え、サムネ量産などは実務責任者（クロコン）がいつでも対応します。
