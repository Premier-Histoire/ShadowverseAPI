
# Shadowverse-wb
言語の変更はリクエストヘッダーにLangを追加して以下の値を使う。
```
ja : "日本語"	//デフォルト
en : "English"
ko : "한국어"
cht: "繁體中文"
chs: "简体中文"
```

## パックカードリスト

https://shadowverse-wb.com/web/CardSet/cardList?card_set_id= `{パックID}`

```
【パックID】
10000   -> ベーシック   
10001   -> 伝説の幕開け
```
## カードリスト
https://shadowverse-wb.com/web/CardList/cardList?offset= `{オフセット値}` &class= `{クラスID}` &cost= `{コストの値}`

```
【クラスID】
0   ->  ニュートラル
1   ->  エルフ
2   ->  ロイヤル
3   ->  ウィッチ
4   ->  ドラゴン
5   ->  ナイトメア
6   ->  ビショップ
7   ->  ネメシス
```
  

## カード情報
https://shadowverse-wb.com/web/CardList/card?card_id= `{カードID}`

## デッキ情報
https://shadowverse-wb.com/web/DeckBuilder/deckHashDetail?hash= `{デッキハッシュ値}`

太文字の部分
https://shadowverse-wb.com/ja/deck/detail/?popular=1&hash= **`2.7.cQqE.cQqE.cQqE.cR0k.cR0k.cR2I.cR2I.cpBc.cpBc.cpBc.cpBw.cpBw.cpBw.cpEu.cpEu.cpEu.cpRE.cpRE.cpRO.cpRO.cpUW.cpUW.cpUW.cpgs.cpgs.cpgs.cph0.cph0.cph0.cphK.cphK.cphK.cpwU.cpwU.cpwe.cpwe.cpwe.cpwo.cpwo.cpwo`**

ハッシュ値の2.Xは`クラスID`
cQqEのような値はカード1枚１枚を表してるがエンコード形式は不明
