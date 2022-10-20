# 開発用 Webpack テンプレート(HTML, TypeScript)

自身の開発用テンプレート。
HTML, JavaScript を Webpack でコンパイルするもの。

## 使い方

適当なディレクトリにクローンした後、履歴を削除。

```
git clone [this_repository] [directory_yourself]
git remote rm origin
git checkout --orphan tmp
git commit -m "first commit"
git checkout -B main
git branch -d tmp
```

その後、`npm i` にてパッケージをインストール。

# 🚀 Welcome to your new awesome project!

This project has been created using **webpack-cli**, you can now run

```
npm run build
```

or

```
yarn build
```

to bundle your application
