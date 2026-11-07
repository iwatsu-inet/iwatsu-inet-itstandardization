# Iwatsu-inet IT Infrastructure Standardization Site

GitHub Pages 公開用の静的HTML一式です。

## File structure

- `index.html` : 親サイト / ITインフラ標準化
- `assessment.html` : 兄 / ITインフラ標準化推進（アセスメント工程の詳細）
- `scs-readiness.html` : 弟 / SCS Readiness / SCS評価制度対応
- `assets/favicon.svg`、`assets/favicon-32.png`、`assets/favicon-48.png`、`assets/apple-touch-icon.png` : favicon（IT Infrastructure Standardization の記号のみ。Design System 19）
- `assets/og-standardization.png` : 共有時の画像（トップのOGPタグ）
- `.nojekyll` : GitHub PagesでJekyll処理を無効化するための空ファイル

## Link structure

- `index.html` の In Practice から `assessment.html` と `scs-readiness.html` へ遷移
- `assessment.html` から `scs-readiness.html` へ遷移
- `scs-readiness.html` から `assessment.html` へ遷移

## GitHub Pages deployment

1. GitHubで新規リポジトリを作成
2. このフォルダ内のファイルをリポジトリ直下にアップロード
3. `Settings` → `Pages`
4. `Build and deployment` → `Source` を `Deploy from a branch` に設定
5. Branchを `main`、Folderを `/ (root)` にして保存
6. 数十秒〜数分後に表示されるURLへアクセス

## Local check

ZIPを展開し、`index.html` をブラウザで開いてください。

## 固定文言（ITインフラ標準化の基本ステイトメント）

Humanが確定した固定文言である。使うときは、複製・言い換え・短縮・意味の拡張をせず、Design Systemの原文を参照する。

- Decision: `HD-DESIGN-20261107-STANDARDIZATION-BASIC-STATEMENT`（都知事、2026-11-07）
- 原文の所在: `iwatsu-inet/iwatsu-inet-design-system` の `design-system-v2.1-visual-language`、`working/v2.1/16_OUTPUT_LANGUAGE_AND_LEAD_POLICY_20260923.md` §9.1
- 確定時のコミット: `8fe650f`。Missionで使うときは、living branchのHEADをresolveし、使用したimmutable refを記録する。
- 岩通アイネット自身のステイトメントであり、SCS評価制度などの制度の公式な定義ではない。変更にはHumanの承認が必要。
