# 『意味がわかるAI入門』読書会

- 課題図書: [次田瞬『意味がわかるAI入門 ─自然言語処理をめぐる哲学の挑戦』(筑摩書房、2023年)](https://www.chikumashobo.co.jp/product/9784480017895/)

## レジュメ

- [序章 哲学者、大規模言語モデルに興味を持つ (AIと人間並の知能三度目のAIブームと機械学習 ほか)](<0-哲学者、大規模言語モデルに興味を持つ>)
- [第1章 AIの歴史――心の哲学を補助線として (ダートマス会議にはじまる第一次AIブーム―「一人で立てたよ!」 ほか)](<1-AIの歴史——心の哲学を補助線として>)
- [第2章 自然言語処理の現在――言語哲学を補助線として (AIは言葉の意味を理解すると思いますか?意味に対する伝統的アプローチ ほか)](<2-自然言語処理の現在>)
- [終章 機械に心は宿るのか? (AGIの誕生、待ったなし?評価者の主観を取り込んだテスト―チューリングテスト ほか)](<3-終-機械に心は宿るのか>)

## マニュアル: レジュメの作成・編集

### 準備

1. GitHub のアカウントを作成し，SSH の鍵の生成とGitHubへの登録をして，自分の作ったアカウントで正常に commit，push ができるか確認後，飯田(<flashingwind@gmail.com>)にそのメールアドレスを通知してください。このレポジトリへの権限を登録します。
1. ローカル環境でプレビューしたい場合，適当な Markdown エディター(VSCode+Markdow 用拡張など)か，[docsify cli](https://github.com/docsifyjs/docsify-cli)を使う

### ブラウザーで編集する場合

1. 少量の編集ならば，[この画面](https://github.com/philomath-club/ohnishi-ronrigaku)の上の方から対象のファイルをを見つけて開き，ペンアイコンで編集。または`Add file`→`Create new file`で新規作成する。
2. `Commit changes…`により保存する(コメントはデフォルトのままでもかまいません)。

### PCで編集する場合

1. ドキュメントを保存しておきたい場所でターミナル(コマンドプロンプト)を開く
2. (初回のみ)クローン

   ```bash
   git clone git@github.com:philomath-club/ohnishi-ronrigaku.git
   cd ohnishi-ronrigaku
   ```

3. (2回目以降)最新の状態をプル。4 の操作後のフォルダー(ohnishi-ronrigaku)で，

   ```bash
   cd ohnishi-ronrigaku
   git pull
   ```

4. Markdown 形式で，ファイルを作成・編集: ohnishi-ronrigakuフォルダーで，VSCode起動。左のファイルリストから適当な過去の.mdファイルを開き，別名保存してテンプレートとしてください。

   ```bash
   code . #VSCodeの場合
   ```

5. 終わったらコミット，GitHub へプッシュ: 4 の操作後のフォルダー(ohnishi-ronrigaku)で，

   ```bash
   git add .
   git commit -m "I部1章追加"
   git push
   ```

   -m に渡す内容(コメント部分)は編集内容に合わせて変更してください。

### 連絡先

- 連絡先・マニュアルと技術的な面の管理: 飯田(<flashingwind@gmail.com>)

## 引用・著作権・ライセンス

課題図書の断片等を法令上の「引用」の範囲で引用している場合がありますが，これらの著作権は元の著作者に帰属します。商標なども同様です。

レジュメ全体，ウェブサイト全体の著作権は任意団体「哲学読書会」に帰属します。MITライセンスで提供しています。転載したり，配布するような場合は，ライセンスに従って下記の著作権表示を明示してください。また，本文には課題図書などからの引用を含むため課題図書も明示してください。

Copyright (c) 2023-2024 哲学読書会(philomath-club). These documents are licensed under [the MIT License](LICENSE)
