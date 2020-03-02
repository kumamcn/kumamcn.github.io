
KumaMCN Github Pages
====

KumaMCN Github Pages and SourceCode for KumaMCN member.

## Description

kumamcnのGithub Pagesをメンバー間で編集するためのソースコード

Hugoで静的ファイルを生成し、Github Pagesでホスティング

## Requirement

- テキストエディタ
- Gitクライアント
- Hugo (v0.65で動作確認)

## Usage

```
kumamcn/kumamcn.github.ioをfork
$ git clone <forkしたリポジトリURL>
$ cd kumamcn.github.io
$ git submodule init
$ git submodule update
$ hugo server
ローカルサーバで動作確認ができる
$ hugo
docs/以下に生成されるので、それも含めてコミットすること
```

## Contribution

1. Fork it ( [https://github.com/kumamcn/kumamcn.github.io/fork](https://github.com/kumamcn/kumamcn.github.io/fork) )
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create new Pull Request

