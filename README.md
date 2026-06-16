# Iwatsu-inet IT Infrastructure Standardization Site

GitHub Pages 公開用の静的HTML一式です。

## File structure

- `index.html` : 親サイト / ITインフラ標準化
- `assessment.html` : 兄 / ITインフラ標準化アセスメント
- `scs-readiness.html` : 弟 / SCS Readiness / SCS評価制度対応
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
