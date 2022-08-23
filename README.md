# slack-api-slack2

## NodeJSとSlack APIによるいまどきのネットワークプログラミング

### Slack APIを用いたアプリケーション その2

Slackのワークスペースとチャネルを作成し、イベントやコマンドへの応答とファイルをアップロードするアプリケーションを開発するときに必要な設定を習得する。挨拶のコマンドを送信すると自動応答するシンプルなスラッシュコマンドを実装する。

[動作確認の手順]

1. スラッシュコマンド/helloが準備したSlackアプリに登録されていることを確認する
1. コマンドプロンプトを開き、ダウンロードしたフォルダへ移動する
1. npm installコマンドでアプリに依存するパッケージをインストールする
1. .envファイルの環境変数SLACK_BOT_TOKENとSLACK_APP_TOKENに作成したSlackアプリのユーザートークンとアプリトークンを設定する
1. アプリを起動する
    $ node ./app.js
1. 準備したワークスペースを開く
1. Slackアプリをインストールしたチャネルのメッセージ欄に「/hello」と入力する
1. 「こんにちは <ユーザー名>!」と返信があるか確認する
