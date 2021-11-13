# Zenn CLI

* [📘 How to use](https://zenn.dev/zenn/articles/zenn-cli-guide)

# memo

## 記事の作成
```
$ npx zenn new:article
```

## プレビュー
```
$ npx zenn preview
```

## 記事の公開
> 記事を zenn.dev 上で公開するにはpublishedオプションがtrueになっていることを確認したうえで、ファイルをコミットし、Zenn と連携されている GitHub リポジトリにプッシュします。
Zenn と連携したリポジトリの登録ブランチにプッシュされると、同期（デプロイ）が開始されます。

## 記事の更新
> 記事の更新を行う場合も、markdownファイルを編集し、GitHub リポジトリへプッシュするだけで OK です。このとき slug が同一のものでないと別の記事として作成されてしまうので注意しましょう。

## 記事の削除
> 削除はダッシュボードから行います。安全のため、articlesディレクトリからmarkdownファイルを削除しても zenn.dev 上では削除はされません。