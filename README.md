# FX Dashboard (Published Output)

このリポジトリは [fx-dashboard-pages] 用のデプロイ専用リポジトリで、`index.html` は
ローカルの投資判断支援ツール（BIS・ECB・OECD・ForexFactoryの実データを毎日取得して
生成）の出力をそのまま公開しているだけです。ソースコードはこのリポジトリには含まれません。

GitHub Pages: https://kento-hamanishi.github.io/fx-dashboard/

毎朝7時（JST）にローカルのlaunchdジョブが最新データでダッシュボードを再生成し、
このリポジトリへ自動でコミット・プッシュしています。
