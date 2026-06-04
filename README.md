.github.io（GitHub Pages）は、GitHubのリポジトリから直接静的ウェブサイトを無料でホストできるサービスです。 [1, 2] 
正しい使い方の核となるのは、リポジトリの命名規則と公開設定（Pages設定）の2点です。
## 1. リポジトリの作成と正しい命名
個人のプロフィールサイトやポートフォリオを作成する場合、リポジトリ名は以下の形式にする必要があります。

* リポジトリ名: {ユーザー名}.github.io
* 例：あなたのユーザー名が taro なら taro.github.io
   * 重要: ユーザー名と完全に一致させる必要があります。大文字が含まれる場合は小文字で入力してください。 [3, 4, 5, 6, 7] 
* 

## 2. ファイルの準備
サイトのトップページとして表示されるファイルは、リポジトリのルート（一番上の階層）に置く必要があります。 [1, 8] 

* 必須ファイル: index.html（または index.md / README.md） [9, 10] 
* 構成例:
* index.html
   * style.css
   * script.js
   * /images/（画像フォルダなど）
* 

## 3. 設定方法（公開手順）
リポジトリを作成し、ファイルをアップロード（またはプッシュ）した後の設定手順です。 [7, 11] 

   1. GitHub上の対象リポジトリを開き、「Settings」タブをクリックします。 [4, 12] 
   2. 左サイドメニューの「Code and automation」セクションにある「Pages」を選択します。 [7, 12] 
   3. 「Build and deployment」セクションの「Source」を 「Deploy from a branch」 に設定します。 [12] 
   4. 「Branch」のドロップダウンから公開したいブランチ（通常は main）を選択し、その横のフォルダ設定が /(root) になっていることを確認して「Save」をクリックします。 [10, 12] 
   5. 数分待つと、画面上部に「Your site is live at...」というメッセージとURLが表示されます。 [12, 13] 

[Getting Started with GitHub Pages](https://www.youtube.com/watch?v=QyFcl_Fba-k&t=199), YouTube · Net Ninja · 2021 M02 19
## 便利な機能と注意点

* カスタムドメイン: 独自ドメインを適用することも可能です。「Pages」設定内の「Custom domain」にドメイン名を入力し、DNS設定（CNAMEレコード等）を行います。 [14, 15] 
* 自動更新: 指定したブランチ（mainなど）にファイルをプッシュするだけで、サイトの内容は自動的に更新されます。 [16] 
* 制限: GitHub Pagesは静的サイト専用です。PHPやPython(Django/Flask)などのサーバーサイド言語は動作しません。 [9] 
* 公開範囲: 無料プランの場合、リポジトリを Public（公開） に設定する必要があります。 [6, 17] 
* 

さらに詳しく知りたい特定のステップ（例：独自ドメインの紐付けやReactなどのフレームワークを使った公開方法）はありますか？

[1] [https://www.youtube.com](https://www.youtube.com/watch?v=ZwG9jwit2Ho)
[2] [https://www.youtube.com](https://www.youtube.com/watch?v=Awnsuyq80xY)
[3] [https://docs.github.com](https://docs.github.com/ja/pages/getting-started-with-github-pages/creating-a-github-pages-site)
[4] [https://docs.github.com](https://docs.github.com/ja/pages/quickstart)
[5] [https://docs.github.com](https://docs.github.com/ja/pages/quickstart)
[6] [https://saycon.co.jp](https://saycon.co.jp/archives/neta/github-pages%E3%82%92%E4%BD%BF%E3%81%A3%E3%81%A6%E7%B0%A1%E5%8D%98%E3%81%AB%E3%82%A6%E3%82%A7%E3%83%96%E3%82%B5%E3%82%A4%E3%83%88%E3%82%92%E5%85%AC%E9%96%8B%E3%81%97%E3%82%88%E3%81%86)
[7] [https://www.plainconcepts.com](https://www.plainconcepts.com/github-pages/)
[8] [https://mukai-lab.info](https://mukai-lab.info/pages/tech/github/github-usage/)
[9] [https://www.youtube.com](https://www.youtube.com/watch?v=OltY8JIaP-4)
[10] [https://github.com](https://github.com/jdevstatic/github-pages-tutorial/blob/main/README.md)
[11] [https://career.levtech.jp](https://career.levtech.jp/guide/knowhow/article/61013/)
[12] [https://docs.github.com](https://docs.github.com/pages/quickstart)
[13] [https://note.com](https://note.com/wood_bell919/n/n17df45e760fd)
[14] [https://zenn.dev](https://zenn.dev/donchan922/articles/59c54fe659128294bb65)
[15] [https://www.folklore.place](https://www.folklore.place/techblog/2024/08/20)
[16] [https://www.issoh.co.jp](https://www.issoh.co.jp/tech/details/5875/)
[17] [https://qiita.com](https://qiita.com/mutsuki15/items/53f59e72ee23eae6c2c0)
