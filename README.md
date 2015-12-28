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
 
