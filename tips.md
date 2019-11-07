Vueのプログラミングスキル
Vuetifyのスキル
postgresql



PHP 7.26
Veu 3.9.3
postgresql
Nginx
xammp
ag-grid



便利ツール
Chocolatey
busybox64.exe
きゃぷつれ
マターモスト



-- A5 機能
-- 検索結果に対して右クリックでフィルターがかけれる






// 新規参画時のためにやることリストを作成する



// エクセル
リボンショートカットを活用する。



// CLaunch
shift x 2 で設定

ctrl x 2 クリップボード使用不可
alt x 2 クリップボードで使用不可






プログラミング言語
参加したプロジェクト
担当工程
経験年数 キーワードと数字でのフィルタリングしか出来ないことになります。



プロジェクト
商業開発コンサルティング企業　社内システム

プログラミング言語
PHP 7.26
Veu.js 3.9.3


担当工程
基本設計(お客様との折衝はありませんでした)　画面設計(Vue.jsによるモック作成)・
詳細設計
実装
単体テスト
結合テスト



### Vue.js

* npm run watch
	* vueファイルを保存する度にvueファイルをコンパイルする。

* メッセージの表示
```
  this.$store.dispatch("message/responseMessage", {
    type: "error",
    text: this.$i18n.t("ag_grid.overlay.no_rows"),
    show: true
  });
```



# 設計書の種類

## 基本設計
* 画面設計(画面イメージ・モック作成)
* 処理概要
* 画面遷移図・画面遷移項目
* 画面項目(画面内の表示仕様の設計)
* イベント処理仕様

## 詳細設計
* イベント処理の詳細

## テーブル設計
* テーブル設計

## 帳票設計
* エクセル・PDF

## バッチ設計
* シェルスクリプト・LaravelやCakePHPのCommandなどの設計




* 強み
得意なフェーズは実装で、効率重視を心がけています
過去の現場で「手が早い」「スケジュールが前倒しになってありがたい」との
評価を頂いております。
人畜無害の平和主義でコミュニケーションも問題ありません。




自分のポリシーとして守破離を重んじてます


効率化を重要視しているため
あらゆるソフト・ハードを利用して


git flowを使用した開発経験は？ある




参画した際のイメージを持つために幾つか確認させてください
* 環境構築について(端末)
* IEDは何か指定 vscodeをメインで使っています
* コミュニケーションツールは導入してますか
* 開発はどのような形で進めていくのか(テストコードやレビュー体制)
* 事前に勉強したほうがいい知識はありますでしょうか？
* 業務知識を得るために、このサイトを見たほうが良いなどあれば教えて頂きたいです。

* 仕様書を書かない場合のディスカッションの場を設けるのか？




やっぱり、その案件ごとに使うフレームワークや言語、
ツールに関してどれだけ知っているか、が相手は1番しりたい部分だからそのあたりかな



#### javascript
* Numeral.js 
* loadash.js

* Vue.js
Vuex
ag-grid.js
vue-pretty-checkbox.js
vue-router.js
vuetify
axios


#### サーバー
Node.js
Apache
Nginx

#### DB操作
A5mk2
pgadmin4
MySQL Workbench

#### ソース管理
SVN
Git

#### ソース管理ツール
TortoiseGit
TortoiseSVN
SourceTree

#### ソース管理ツール(WEB)
GitHub
Bitbucket
GitLub
Gitbucket





###Tips

#### A5mk2

- テーブルをお気に入り登録できる
- フィルターがかけれる
- レコードからインサート・アップデート文が書ける


#### vscode
- Beautify
- Bracket Pair Colorizer
- change-case
- Debugger for Chrome
- DotENV
- ESLint
- Excel Viewer
- Favorites
- Git History
- GitLens
- Japanese
- Markdown PDF
- Markdown Preview Enhanced
- Material Icon Theme
- Night Owl
- PHP Debug
- PHP IntelliSense
- PostgreSQL
- Regex Previewer
- Shortcuts
- SQL Server
- SQLTools
- Terminal Tabs
- TODO Parser
- Todo Tree
- Trailing Semicolon
- Trailing Spaces
- Vetur
- vscode-cheatsheet
- vscode-icons




・スマートフォン用画面製造
5画面　
設計：4人日
製造・単体：5人日

・メール関連処理
メール送信基底処理
メールプレビュー画面
メール一斉送信処理　最大100件
メール本文等に特定の固有タグ置き換え機能実装


・外部公開機能
懇意にしている顧客に対して社内システムを利用する機能

・アクセスログ登録処理


・SSL対応(予定)


経験してきた知識をさらに追求していきたい
個人の強みはどこなのか、どういった分野に興味があるのか
自分はどういった分野が得意でどういったアウトプットに貢献できるか

フロントエンド = ユーザーが見ている画面のデザイン
サーバーサイド = サーバーでプログラムの実行・管理

得意なことは長年培ってきたサーバーサイドの技術ですが
現在はASPやウェブデザイン(UI/UX)に興味を持ち独学・実務で
フロントエンドの技術を磨いております

新しい技術にはとても興味がある





### lodash.jsとは
https://lodash.com/

A modern JavaScript utility library delivering modularity, performance & extras.
```
ユーティリティー（なんか便利）関数を集めたやつ
めっちゃかるい
```
という特徴を持つライブラリです。


------------------------------------------------------------------------------------ 
// routes.jsで苦戦した話
実際は別の場所で作成されたroutes.jsを編集していた？
怪しいときはファイル名をマウスオーバーしてパスが出てこないときは
破棄してもう一度ファイルを開き直しましょう。
------------------------------------------------------------------------------------ 
// ストアドで１時間苦戦した部分
structure of query does not match function result type
このエラーが発生した場合は、RETURNS TABLEのカラムの型が間違っている
もとのSQLでSELECT文を関数で変更し、AS hogehogeとした場合
RETURNS TABLE に記載するカラムの型はtextに変更しなければならない。
------------------------------------------------------------------------------------

# Tips
---
## 使用言語
---
Laravel 5.6.33
Vue.js  3.9.3
```
バージョン確認
php artisan --version
vue --version
```



---
## Velocity.jsとは
---
Velocity.jsとは  
jQueryのプラグイン。  
$.animateと互換性を持ち、さらに高機能で非常に軽快なアニメーションをする。  
(このライブラリは使ってない、個人の興味)  
### 種類
```
each  
map  
mapValues  
mapKeys  
groupBy / invertBy  
filter
```

---
## $emit
---
https://www.hypertextcandy.com/vuejs-components-introduction-emit-events  

今回紹介する $emit は、カスタム要素の発行するイベントです。  
変更した props を $emit で親に伝達します。  
$emit の第1引数には「イベント名」、第2引数には「イベントデータ」を渡します。  




---
## 用語集
---
|用語名|読み方|解説|
|---|---|---|
|axios.js|あくしおす（どっとじぇーえす）|HTTP通信を超簡単に行うことができるJavaScriptライブラリ。<br>HTTP通信と言うと用途がわかりづらいが、主にJSONの取得に利用されることが多い。
|Vuetify|びゅーてぃふぁい|uetifyは、Vue.js用のUIコンポーネントフレームワークです。マテリアルデザインの手法に基づいた豊富なコンポーネントを提供しています。
|||
|||
|||
|||
|||
|||
|||
|||


単体テストに画面の幅テストを追加する？(PC画面)
・クローム
・IE


## プルダウンの中身取得例
---
```
// リストの取得
RequestSelectItem.fetchItemsList({
	// 欲しいアイテムリスト名を記述
	generalPurposeItems: [GENERAL_PURPOSE_ITEMS.PROPOSAL_STATUS,
	GENERAL_PURPOSE_ITEMS.PROPOSAL_FIXED_PHRASE],
	master: [MASTER_ITEMS.USER]
}).then(response => {
	this.itemsList = response;
});
```



---
## Vue ライフスタイル
---
ライフサイクル
Vueインスタンスのライフサイクルは次の通りです。それぞれのタイミングでフックして処理を書くことができます。
```
beforeCreate
Created
beforeMount
mounted
(DOM描画)
(DOMの変更を検知)
beforeUpdate
updated
( this.$destroy(); )
beforeDestroy
Destroyed
```

---
## パラメータの受渡し
---
```
//メール一斉送信画面へ
this.$router.push({
	name: "mail.sendMail",
	params: { objectNoList: this.form.isMailList, tenantNoList: tenantNoList, path: this.$route.path }
});
```


## Chocolatey すごく便利
windowsのパッケージ管理ソフト  
コマンドラインやxmlファイルでかんたんにソフトをダウンロードできる  
ダウンロードできるソフトは決まっているが・・・
cinst googlejapaneseinput google-chrome-x64


## 便利ソフト

|ソフト名|説明|URL|
|---|---|---|
|Everything|ファイル名検索||
|Clibor|クリップボード履歴管理||
|busybox64.exe|WindowsでLinuxコマンドが打てる||
|chocolatey|ファイル管理ソフト||



# 気をつけること
SQLで原因のわからないエラーが発生した場合   
その文章が文字列かどうか確認してください  
文字列だった場合、シングルクォーテーション''を入れると  
エラーが発生するので''''と四つ設定してください  
  
これがわからず一時間ほどロスしてるので気をつけてください  




### SSH化対応

#### SSL認証について
##### 認証の種類
SSL証明書にはいくつか認証型に種類があります。

|名前|説明|信頼性|
|---|---|---|
|ドメイン認証|ドメインの使用権の有無のみ|低|
|企業実在性認証|ドメイン+サイト運営団体の実在性の確認(電話認証など)|高|
|EV認証|サイト運営団体の厳格な確認|最高|

https://www.cpi.ad.jp/column/column08/


#### SSLの3つの認証レベル（下にいくほど、レベルが高い認証です）
DV（Domain Validation）：ドメイン認証
OV（Organization Validation）：企業認証
EV（Extended Validation）


企業はOVかEV認証を取得する。  

#### 取得後
証明書(hogehoge.crt)  
中間証明書(piyopiyo.crt)  
この2つを取得できているはずなのでサーバーに保管する

保存するディレクトリは基本は /etc/pki/tls/certs





#### 実際にSSL証明書を取得する
SSL証明書を取得するまでのざっくりした流れ
1. 秘密鍵の作成
2. 秘密鍵を用いてcsrを作成
3. csrを認証局のブラウザで貼り付け申し込む
4. 承認メールが届くので、承認して、証明書を発行してもらう。
5. 証明書をサーバーに設置して、再起動
6. 終了
※現在の証明書の署名アルゴリズムには、SHA-1ではなくSHA-2(SHA-256)を  
使用することが推奨されているため、sha-256で作ることを前提としてます。  





#### ローカル環境のSSL対応を行ってみる

1. Chocolateyのインストール
https://qiita.com/konta220/items/95b40b4647a737cb51aa

管理者権限のコマンドプロンプトまたはPowerShellで以下のコマンドを実行し、インストール  
```
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

以下コマンドでバージョンが表示されればインストール完了
```
choco -v
```

2. mkcertのインストール
https://qiita.com/rkunihiro/items/530b5dc685bd3bff2082

管理者権限のコマンドプロンプトまたはPowerShellで以下のコマンドを実行し、インストール  
```
choco install mkcert
```

3. CA証明書をインストール (初回のみ)
```
$ mkcert --install
```


