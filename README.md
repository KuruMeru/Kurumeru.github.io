# Kurumeru.github.io

Memoria の公式ページとプライバシーポリシーを公開するための GitHub Pages リポジトリです。

## 公開 URL

https://kurumeru.github.io/

## 配信設定

- GitHub Pages は `main` ブランチのリポジトリルートをそのまま配信する想定です。
- ビルド工程はありません。HTML/CSS を更新して `main` に反映すると公開内容も更新されます。

## 主なファイル

- `index.html`: Memoria のトップページ
- `Memoria_PrivacyPolicy.html`: プライバシーポリシー
- `CommonStyle.css`: 共通スタイル
- `assets/screenshots/`: トップページで使用するスクリーンショット
- `assets/icons/`: アプリアイコン、ファビコン、Apple Touch Icon
- `assets/badges/`: Apple 公式の App Store バッジ
- `assets/og/`: SNS やメッセージアプリで共有したときに表示する画像
- `robots.txt`: クローラー向けの案内
- `sitemap.xml`: 公開ページ一覧
- `404.html`: 存在しない URL にアクセスされた場合のページ

## アセットの更新元

- アプリアイコンは `../Memoria-HeatMap-main/Memoria-HeatMap/Assets.xcassets/AppIcon.appiconset/` の `Default.png` と `Dark.png` を使用します。
- トップページの日本語スクリーンショットは、公開中のアプリ版に対応する `../Memoria-HeatMap-release-next/docs/assets/app-store-screenshots/submitted/<version>/iPhone-ja/` から、ヒートマップ、カレンダー、写真一覧の3枚を使用します。
- App Store バッジは Apple 公式の日本語版を使用します。色や文字、縦横比は変更しません。
- 新しいアプリ版で画面や機能が変わった場合だけ、スクリーンショット、機能紹介、OGP画像を更新します。文言や画面に変更がないアプリ更新では、サイト側の作業は不要です。
- `CommonStyle.css` を更新した場合は、各 HTML の `?v=` を新しい値へ揃えます。スクリーンショットを差し替えた場合も、`index.html` の画像URLにある `?v=` を公開するアプリ版へ更新し、古いキャッシュが残らないようにします。
