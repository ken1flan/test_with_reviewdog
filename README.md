# README

RailsプロジェクトにGitHub Actionsとreviewdogを使って、
自動コードレビューを行うサンプルです。

- [reviewdog](https://github.com/reviewdog/reviewdog)
- [rubocop](https://github.com/rubocop-hq/rubocop)
- [brakeman](https://github.com/presidentbeef/brakeman)
- [reek](https://github.com/troessner/reek)
- [haml-lint](https://github.com/sds/haml-lint)
- [eslint](https://github.com/eslint/eslint)
- [stylelint](https://github.com/stylelint/stylelint)

自動レビューはGitHubにプルリクエストを作成すると行われるようになっています。
プルリクエストを出す前に手元で確認したいときには↓のようにコマンドラインでreviewdogを実行します。

```console
$ reviewdog -diff="git diff main"
```
