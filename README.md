<header>

<!--
<<< 作成者メモ: コースヘッダー >>>
このテンプレートを使用してコースを作成する方法の詳細については、<https://skills.github.com/quickstart> をご覧ください。
1280×640 の画像、文頭大文字で書かれたコース名、そして強調表示を使った簡潔な説明を含めてください。
リポジトリ設定で、テンプレートリポジトリを有効にし、1280×640 のソーシャル画像を追加し、ヘッドブランチの自動削除を設定します。
「About」の横に説明とタグを追加し、リリース、パッケージ、環境を無効にします。
オープンソースライセンスを追加します。GitHub は MIT ライセンスを使用しています。
-->

# リリースベースのワークフローを作成する

_GitHubフローを基盤として構築されたリリースベースのワークフローを作成します。_

</header>

<!--
<<< 著者メモ: ステップ 3 >>>
前のステップへの同意からこのステップを開始してください。
用語を定義し、docs.github.com へのリンクを貼ってください。
-->

## ステップ 3: リリース プルリクエストを開く

_新機能の追加、お疲れ様です :smile:_

### リリースブランチと `main`

リリースブランチと main ブランチの間で、できるだけ早くプルリクエストを開くことをお勧めします。プルリクエストは長期間オープンのままでも問題ありません。

一般的に、プルリクエストの説明には以下を含めることができます。

- プルリクエストで対処する [問題への参照](https://docs.github.com/en/articles/basic-writing-and-formatting-syntax/#mentioning-people-and-teams)。
- プルリクエストで提案された変更内容の説明。
- 提案された変更のレビュー担当者またはチームへの [@メンション](https://docs.github.com/en/articles/basic-writing-and-formatting-syntax/#mentioning-people-and-teams)。

このプルリクエストの作成を迅速化するために、リポジトリにプルリクエストテンプレートを追加しました。プルリクエストを作成すると、デフォルトのテキストが自動的に表示されます。これにより、必要な情報をすべて特定して入力するのに役立ちます。テンプレートの内容を使用しない場合は、プルリクエストからテキストを削除し、プルリクエストのメッセージに置き換えてください。

### :keyboard: アクティビティ: リリースプルリクエストを開く

`release-v1.0` ブランチと `main` ブランチを比較する新しいプルリクエストを作成しましょう。

1. `base: main` と `compare: release-v1.0` を指定して、**new pull request** を開きます。
2. プルリクエストのタイトルが`release-v1.0`であることを確認してください。
3. プルリクエストの本文に詳細な内容を記載してください。例を以下に示します。
```
## Description:
- Changed page background color to black.
- Changed game text color to green.
```
4. **「Create pull request」** をクリックします。
5. 約20秒待ってから、このページ（手順を実行しているページ）を更新します。[GitHub Actions](https://docs.github.com/en/actions) が自動的に次のステップに更新されます。

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
