# Indexページの作成とGit共有の準備

チーム内でのページ共有（GitHub Pages等を想定）をスムーズに行うため、トップページとなる `index.html` を作成し、既存の各ページ（LP.html, bira.html）への導線を設けます。

## Proposed Changes

### Indexページ
#### [NEW] index.html
- モダンで視覚的にわかりやすいデザイン（Tailwind CSSを使用）
- 現在存在するページ（LP.html, bira.html）へのリンクカードを配置
- 「つなげモン シリーズ ドキュメント一覧」といったタイトルにする

### Git設定 (必要に応じて)
- 現在のディレクトリがGit管理下にあるか確認し、未コミットの変更があれば追加して共有の準備を整えます。

## Verification Plan

### Manual Verification
- `index.html` をブラウザで開き、デザインが崩れていないか、リンクをクリックして各ページへ正しく遷移するかを確認します。
- Gitコマンドを用いて、正しくコミット可能な状態になっているか確認します。
