# FFXIV_PatchPi
おふざけ

URL: http://kogarasi.github.io/FFXIV_PatchPi/

# Get Started

Rubyが入ってる前提でお話。
環境によっては細かい対応が必要になるけど、大筋はこんな感じで。

1. Bundlerをインストールする
2. リポジトリからクローン
3. クローンしたリポジトリでBundle経由でGemを入れる
4. Middlemanをサーバーモードで起動させる
5. ブラウザで確認 -> localhost:4567

### Install Bundler

```bash
gem install bundler
```

### Cloning Repository

```bash
git clone git@github.com:Kogarasi/FFXIV_PatchPi.git
```

### Service Middleman

```bash
middleman server
```
 

# Create Static Page

```bash
middleman build
```

実行するとbuildディレクトリに静的ページがはき出されます。

```bash
middleman deploy
```

実行するとbuildディレクトリの中身をgh-pagesにコミット/プッシュしてくれます

# Learn More...

wikiに方針とか書きました。
https://github.com/Kogarasi/FFXIV_PatchPi/wiki
