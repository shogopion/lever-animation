こんにちは！テコの原理について、小学生にも分かりやすく、さわって学べるアニメーションをご用意しました。

このアニメーションでは、シーソーのような板（テコ）、それを支える三角の台（支点）、持ち上げる荷物（おもり）、そして荷物を持ち上げるために押す力（力点）が出てきます。

「支点のいち」スライダーを動かして支点の場所を変えたり、「押す力」スライダーで力の大きさを変えたりすると、テコがどのように傾くか、荷物が持ち上がるかどうかが変わります。

下の説明文には、どうしてそうなるのか、ヒントが出てきます。
「リセット」ボタンを押すと、最初の状態にもどります。

いろいろ試して、テコの面白い性質を発見してみてくださいね！

ーーーーーーーーーーーーー
#GitHub Pagesでアニメーションを公開する手順このガイドでは、作成した「テコの原理 アニメーション」のHTMLファイルをGitHub Pagesを使ってインターネットに公開する手順を説明します。
##ステップ1: GitHubアカウントの準備GitHubアカウントの作成:まだGitHubアカウントをお持ちでない場合は、https://github.com/ にアクセスしてアカウントを作成してください。既にアカウントをお持ちの場合は、サインインしてください。

##ステップ2: 新しいリポジトリの作成新しいリポジトリを作成:GitHubにサインイン後、画面右上の「+」アイコンをクリックし、「New repository」を選択します。[画像: GitHubの新しいリポジトリ作成画面のイメージ]リポジトリ情報を入力:Repository name: 好きなリポジトリ名を入力します。例えば lever-animation や teko-no-genri など、分かりやすい名前が良いでしょう。（注意: ここで入力する名前が、公開されるURLの一部になります。）Description (任意): リポジトリの説明を入力します。例：「テコの原理を学ぶためのインタラクティブなアニメーション」Public/Private: 「Public」を選択します。GitHub Pagesの無料利用では、リポジトリをPublicにする必要があります。Initialize this repository with:「Add a README file」にチェックを入れると、リポジトリの説明などを記述するファイルが自動で作成されるので便利です（任意）。入力が終わったら、「Create repository」ボタンをクリックします。

##ステップ3: HTMLファイルの準備ファイル名を変更:あなたが作成した「テコの原理 アニメーション」のHTMLファイルの名前を index.html に変更してください。GitHub Pagesは、デフォルトで index.html という名前のファイルを探して表示するためです。ファイルの内容確認:提供されたHTMLコードが、この index.html ファイルに正しく保存されていることを確認してください。

##ステップ4: index.html ファイルをリポジトリにアップロードリポジトリにファイルを追加する方法はいくつかありますが、ここではブラウザから直接アップロードする簡単な方法を説明します。「Add file」をクリック:作成したリポジトリのページを開き、「Add file」ボタンをクリックし、ドロップダウンメニューから「Upload files」を選択します。[画像: GitHubリポジトリの「Add file」ボタンと「Upload files」オプションのイメージ]ファイルをアップロード:「drag files here to add them to your repository」と表示されたエリアに、準備した index.html ファイルをドラッグ＆ドロップするか、「choose your files」をクリックしてファイルを選択します。変更をコミット:ファイルがアップロードされると、ページ下部に「Commit changes」というセクションが表示されます。最初のコミットメッセージ（例: Initial commit や Add lever animation HTML）を入力します。「Commit directly to the main branch」が選択されていることを確認します。「Commit changes」ボタンをクリックします。これでファイルがリポジトリに保存されます。

##ステップ5: GitHub Pagesの設定と公開リポジトリの「Settings」に移動:リポジトリのページの上部にあるタブから「Settings」をクリックします。[画像: GitHubリポジトリの「Settings」タブのイメージ]「Pages」セクションを選択:左側のサイドバーメニューから「Pages」を選択します。公開ソースを設定:「Source」または「Build and deployment」というセクションがあります。（UIは時々変更されます）「Deploy from a branch」が選択されていることを確認します。Branch: ドロップダウンメニューから「main」（またはファイルを追加したブランチ名、通常はmainかmaster）を選択し、「/ (root)」フォルダを選択して、「Save」ボタンをクリックします。[画像: GitHub Pagesの設定画面でブランチを選択する部分のイメージ]公開を確認:「Save」をクリックすると、ページが再読み込みされ、しばらくすると「Your site is live at https://<あなたのユーザー名>.github.io/<リポジトリ名>/」のようなメッセージとURLが表示されます。[画像: GitHub Pagesで公開されたURLが表示されている画面のイメージ]このURLが、あなたのアニメーションが公開されているアドレスです。表示されるまでに数分かかることがあります。ステップ6: 公開されたページを確認URLにアクセス:ステップ5で表示されたURLをクリックするか、ブラウザのアドレスバーにコピー＆ペーストしてアクセスします。「テコの原理 アニメーション」が表示されれば成功です！トラブルシューティング表示されない場合:ファイル名が index.html になっているか確認してください。GitHub Pagesの設定で正しいブランチ (main) とフォルダ (/ (root)) が選択されているか確認してください。ブラウザのキャッシュをクリアしてみるか、数分待ってから再度アクセスしてみてください。リポジトリが「Public」になっているか確認してください。レイアウトが崩れる場合:HTML内のCSSやJavaScriptのパス指定に問題がないか確認してください（今回のコードは外部ファイルを参照していないので、通常は問題ありません）。

##これで、世界中の誰でもあなたのアニメーションを見ることができるようになりました！もし途中で分からない点があれば、お気軽にご質問ください。
