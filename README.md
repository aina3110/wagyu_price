# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？

- リモートリポジトリ：インターネット上に配置して複数人で共有するためのリポジトリ
- ローカルリポジトリ：開発者が使うために自分のPC上に配置するためのリポジトリ


## プッシュとマージの違いは何でしょうか？

- プッシュ：ローカルリポジトリの内容をリモートリポジトリに反映する
- マージ：別のブランチの作業内容をブランチに取り込む

- 現場では実際どちらを使うでしょうか？：プルリクエスト
- また、↑その理由はなぜでしょうか？：バグの発生を抑えるため、他の人からのコードレビューが必要だから

## コミットとプッシュの違い

- コミット：変更内容を保存する
- プッシュ：変更内容をリモートリポジトリに反映する


## コミットのメッセージはどのように書いてあげるのが最適でしょうか？

編集内容を正確に表すように書いてあげる
- プレフィックスとは：先頭に付ける単語や番号などの特定の文字列
- コミットメッセージのプレフィックスの例：add、change、style、fix

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？

- ローカル：ローカルのワーキングブランチをローカルのマスターブランチにマージする
- プルリクエスト：事前にバグを発見できるように内容変更をマージしてくださいという依頼を行う

## コンフリクトを起こしてしまった場合、どう対処すべきですか？

1. 先マージされた変更内容を取り込む
2. 後にマージしようとしている変更内容を取り込む
3. どちらの変更内容も取り込みます

- 自分とAさんのコードがバッティングしてコンフリクトが起きた場合、自分の視点だけで考えて修正して良いでしょうか？：Aさんの視点も考慮して修正を行う