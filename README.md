# botpress-examples
Chatbot examples built with Botpress

## bot_qna-with-fallback

質問応答ボットのサンプルです。
ユーザー発話に対してQnAが直接応答されない場合には、エンティティに基づくQnA検索結果を表示して、
検索結果からユーザーに選んでもらう仕組みを実現しています。

### 使い方

1. archives/bot_qna-with-fallback.tgz をインポートしてボットを作成
2. サンプルとして入っているQnAを削除して、QnAを登録
3. 登録したQnAのQuestionのテキストに含まれるキーワードを、Entityとして登録（サンプルは削除）
4. 学習を実行
