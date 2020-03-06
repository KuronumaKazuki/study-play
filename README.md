

# step0

環境構築は省く

```
$ sbt new playframework/play-scala-seed.g8
This template generates a Play Scala project 

name [play-scala-seed]: study-play
organization [com.example]: com.kokodayo
$ cd study-play
$ sbt run 
$ curl http://localhost:9000/
```
※ ゴミ除去済み(restAPIなのでhtml等除去)

フォルダ構成やbuild.sbtについて説明をする




## step1 テストを書く

### 説明内容
- リファクタリング、アンチパターンについて説明
- テストの書き方。

できればスクラムデベロッパーの資料もってきておきたい。

### 課題
 メンバーの配列から20歳以下の人数をカウントして返す

### 参考URL
- [SourceMaking](https://sourcemaking.com/)
- [これだけは覚えたい、ユニットテストを書くための４つのデザイン](https://qiita.com/koduki/items/4fde43b68fe450c6a5d8)

## step2 TODOのrestAPIを作る

※ 先にモノリシックで作らせたほうが良さそう

### 説明内容
- 自分ならどう作るか？を説明
- restAPIの設計について

#### 自分の手順
 
1. まずAPIのresponseを作ります。直接stringでベタ書きでよい。ただ内容はできるだけ本番のデータを想定する。
1. 


### 課題
 API(get)のレスポンスを
 
### 参考

- [翻訳: WebAPI 設計のベストプラクティス](https://qiita.com/mserizawa/items/b833e407d89abd21ee72)

## step? プロジェクト分け

### 説明内容
- DDDとは?
- クリーンアーキテクチャとは?

### 課題


- [実装クリーンアーキテクチャ](https://qiita.com/nrslib/items/a5f902c4defc83bd46b8)

## step3 TODOのrestAPIの設計



## おすすめ教材

- [Dwango Scala初学者向けの学習テキスト](https://scala-text.github.io/scala_text/)