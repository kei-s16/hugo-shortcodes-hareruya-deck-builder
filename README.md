# hugo-shortcodes-hareruya-deck-builder
## これはなに？
晴れる屋のデッキ埋め込み機能をHugoのサイト上でも利用できるようにするためのショートコード。

## 導入
自分の `layout/shortcodes` 以下にこのリポジトリの `layout/shortcodes` 以下のファイルを置く。  
コピーでもGitのsubmoduleでもOK。  

## 使い方
### 前準備
晴れる屋のデッキ埋め込みリンクから `deckid` を取得する。  
限定公開デッキを埋め込む場合は、 `token` も控えておく。  

### 埋め込む
`hareruya_deckembedder` タグを使う。  

```markdown
## 公開デッキの埋め込み
{{< hareruya_deckembedder deckid="ここにdeckidを入れる">}}

## 限定公開デッキの埋め込み
{{< hareruya_deckembedder deckid="ここにdeckidを入れる" token="ここにtokenを入れる" >}}
```
