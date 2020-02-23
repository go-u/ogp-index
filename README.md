![](https://github.com/go-u/ogp-front/workflows/Test/badge.svg)
![](https://github.com/go-u/ogp-front/workflows/Staging/badge.svg)
![](https://github.com/go-u/ogp-front/workflows/Production/badge.svg) 

# OGPギャラリー

## 進捗
1. プロトタイプのリリース  
    - [1日でWeb/Android/iOSアプリ版をリリース](https://twitter.com/go__gou/status/1229944842970652677)   
    - [1日目のWeb版](https://youtu.be/-VZmPOavE8M)   
    - [1日目のアプリ版](https://youtu.be/NcmQW6U2gVA) 
1. ユーザにフィードバックを貰う( ← 現在ここ)
1. 継続的な改善

## コンセプト
開発者の方が利用できるOGP資料数を目指しています。  
[参考資料: バイラル係数を左右するOGPとマイクロブラウザ](https://gigazine.net/news/20191219-microbrowsers-are-everywhere/)

## 機能一覧
- Eメール/パスワード認証
- ソーシャルログイン
- 投稿機能
- ブックマーク機能
- ユーザ画像の更新機能
- [投稿者権限の判定](https://github.com/go-u/ogp-back/blob/master/server/db/schema/user/user.sql)(今は全ユーザ許可)  
などです（プロトタイプ版のため機能は少なめ、バグ出し期間中）  

## ソースコード
- [フロントエンド / E2Eテスト等](https://github.com/go-u/ogp-front)
- [バックエンド / Docker等](https://github.com/go-u/ogp-back)  
**CI/CD**や**ユニットテスト**などのコードも各リポジトリにあります。

## その他
- [Web版](https://ogp-gal.com/)
- [Androidベータ版](https://play.google.com/store/apps/details?id=ogp.gal)
- [iOSベータ版](https://testflight.apple.com/join/nGV3D8ab)
