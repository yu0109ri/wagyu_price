# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？

・リモートリポジトリ：ネット上に配置して複数人で共有するためのリポジトリ
・ローカルリポジトリ：開発者一人ひとりが使用するために自分のPC上に配置するためのリポジトリ

## プッシュとマージの違いは何でしょうか？

・プッシュはローカルの内容をリモートにアップすること
・マージは別のブランチの作業内容を取り込むこと

## コミットとプッシュの違い

・コミットはファイルの編集内容をローカルで登録すること
・プッシュは編集内容をリモートに反映すること

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？

・一目で変更内容がわかるように書く

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？

・ローカルでマージするフローでは、変更内容が共有されないまま（コードレビューされないまま）
リモートに更新が反映されてしまう
・プルリクエストでマージするフローでは、リモートで「変更内容をマージしてください」と依頼を
行ってから変更内容が反映される

## コンフリクトを起こしてしまった場合、どう対処すべきですか？

・エディタを使って、両方の変更内容を取り込んだ処理で上書きすることで両方を取り込む