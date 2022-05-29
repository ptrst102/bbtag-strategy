# BBTAGの攻略Webページをつくっチャオ の段

## 開発環境の構築

### 前提条件

- Windows
- powershellでコマンドを実行

### Git のインストール

[ここ](https://gitforwindows.org/)でダウンロード

クローン

```
git clone https://github.com/ptrst102/bbtag-strategy.git bbtag-strategy
```

### GitHub アカウントの作成

[ここ](https://github.com/)で作成

### Hugo のインストール

[ここ](https://gohugo.io/getting-started/installing/)を参照

クローンしたディレクトリ上で以下のコマンドを実行すると、Webページを http://localhost:1313 上でプレビューできる

```
cd bbtag-strategy
hugo serve -D
```