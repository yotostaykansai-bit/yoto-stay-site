# GitHub／Vercel デプロイ手順

前提：アカウント作成は本人確認とパスワード設定が必要なため、ユーザー本人が行う。パスワードはチャットに送らないこと。Muse側はサイト一式（このフォルダ）を準備済み。

## ユーザーがやること

1. github.com で新規登録する。メールは yotostay.kansai@gmail.com を使う。仕事用アカウントとは分離する。
2. 新規リポジトリを作成する。名前の候補：yoto-stay-site（PublicでもPrivateでも可。Vercel連携はどちらでも可能）。
3. 作成できたら、リポジトリのURLをClaudeに送る。アップロード（git push）はClaude側で手順を案内するか、GitHubのWebアップロードでも可能。
4. vercel.com で「Continue with GitHub」を選び、手順2のGitHubアカウントで登録する。
5. Vercelで「Add New → Project」を選び、手順2のリポジトリをImportする。
6. 設定は初期値のままにする。Framework Presetは Other、Build Commandは空欄、Output Directoryは空欄でよい（静的サイト、ビルド不要）。
7. Deployを押す。発行されたURL（例：yoto-stay-site.vercel.app）をClaudeに送る。
8. 独自ドメインは後回しでよい。先にvercel.appのURLで公開し、ASP申請に使う。

## 公開後にClaudeがやること

1. 公開URLで全ページ（トップEN／JA、記事10本）の表示確認。
2. バリューコマースとAmazonアソシエイトの申請文の下書き作成（申請操作自体はユーザーの承認後に進める）。
3. ASP各社の提携申請リスト作成。

## つまずきポイント

- GitHub登録時の確認メールが届かない場合は、迷惑メールフォルダとメールアドレスの打ち間違いを確認する。
- Vercelでリポジトリが見えない場合は、GitHub側のインストール許可（Vercelアプリへのアクセス許可）を確認する。
