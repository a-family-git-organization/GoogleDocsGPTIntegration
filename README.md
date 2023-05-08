--- この文章はScriptを元にChatGPTで生成しました ---

# GoogleDocsGPTIntegration

このリポジトリは、Googleドキュメント上で選択したテキストとユーザーが入力するプロンプトをGPT APIにリクエストして、出力をGoogleドキュメントの先頭に挿入するスクリプトを管理します。スクリプトは、Google Apps Script上で実行され、サイドバーにUIを提供します。

## 機能
- プロンプト/ロールの入力
- 選択したテキストとプロンプトのリクエスト
- 出力を文書の先頭に挿入
- GPT APIの利用
- サイドバーUI

## 使い方
1. Googleドキュメントを開く
2. [ツール] > [スクリプトエディタ] をクリック
3. スクリプトエディタで新しいプロジェクトを作成
4. スクリプトエディタに、このリポジトリの スクリプト をコピー＆ペースト
5. スクリプトエディタで新しいHTMLファイルを作成し、名前を "Sidebar" とする
6. 新しいHTMLファイルに、このリポジトリの サイドバーのhtml をコピー＆ペースト
7. スクリプトエディタで [ファイル] > [プロジェクトのプロパティ] をクリック
8. [スクリプトのプロパティ] タブで、APIKEY という名前の新しいプロパティを作成し、OpenAIのAPIキーを設定
9. スクリプトエディタで [デプロイ] > [新しいデプロイ] をクリックし、デプロイタイプとして "ウェブアプリ" を選択
10. Googleドキュメントに戻り、[アドオン] > [スクリプトを実行] をクリック
11. サイドバーが表示されるので、必要に応じて設定を変更し、[処理を開始] ボタンをクリック

## 注意事項
- APIキーは他人に漏れないように注意してください。スクリプトのプロパティに設定した場合、他のユーザーがスクリプトエディタにアクセスできなければ安全です。
- GPT APIの利用料が発生することを理解し、利用に注意してください。制限を設けることができますが、このスクリプトでは設定されていません。
