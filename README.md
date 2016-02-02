# masakid.github.io

## 目的
 * ギャラリーサイト
 * 自分の作ったものを置いていく


## 本サイトの作成方法
 * Hugo site generatorによって作成
 * hugoコマンドで記事を生成
 * github pagesへpushして配置

## 記事の生成手順
 
 * 記事生成：プロジェクトのルートディレクトリにて
 
 ```
 $ hugo new post/hogehoge.md
 ```

 テンプレートが生成されるので、記事を書く
 
 * 画像の配置
 
 static/imagesに配置し、記事の中から"[ファイル名](/images/hogehoge.png)で呼び出す

 * preview
 
 ```
 $ hugo server
 ```
 
 * build
 
 ```
 $ hugo
 ```


## 参考記事

[GitHub Pagesでブログ立ち上げ - Hugoを使う](http://tbd.kaitoy.xyz/2015/08/28/using-hugo/)

