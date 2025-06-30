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
<<< 著者メモ: ステップ 4 >>>
前のステップを完了したことを確認することから、このステップを開始します。
用語を定義し、docs.github.com へのリンクを設定します。
-->

## ステップ 4: リリースノートを生成してマージする

_プルリクエストを開いていただきありがとうございます :dancer:_

### 自動生成されるリリースノート

[自動生成されるリリースノート](https://docs.github.com/en/repositories/releasing-projects-on-github/automatically-generated-release-notes) は、GitHub リリースのリリースノートを手動で作成する代わりに、自動的に生成する機能を提供します。自動生成されるリリースノートを使用すると、リリース内容の概要を迅速に生成できます。自動生成されるリリースノートには、マージされたプルリクエストのリスト、リリースへの貢献者のリスト、完全な変更履歴へのリンクが含まれます。また、生成後のリリースノートをカスタマイズすることもできます。

### :keyboard: アクティビティ: リリースノートを生成する

1. 別のタブで、このリポジトリの **Releases** ページに移動します。
   - _ヒント: このページにアクセスするには、リポジトリ上部の **Code** タブをクリックします。次に、リポジトリの説明の下にあるナビゲーションバーから **Releases** 見出しリンクをクリックします。_
2. **Draft a new release** ボタンをクリックします。
3. _Tag version_ のフィールドに「v1.0.0」と指定します。
4. タグドロップダウンの右側にある _Target_ ドロップダウンをクリックし、`release-v1.0` ブランチを選択します。
   - _ヒント: これは、このブランチの変更に基づいてリリースノートを生成するための一時的なものです。_
5. 説明テキストボックスの右上にある **Generate release notes** をクリックします。
6. テキストボックス内のリリースノートを確認し、必要に応じて内容をカスタマイズします。
7. _Target_ ブランチを `main` に戻します。これは、リリースブランチがマージされたらタグを作成するブランチです。
8. 次のステップでこのリリースを公開するため、**Save draft** をクリックします。

これでプルリクエストを [マージ](https://docs.github.com/en/get-started/quickstart/github-glossary#merge) できます。

### :keyboard: アクティビティ: main にマージ

1. 別のタブで、このリポジトリの **Pull request** ページに移動します。
1. **Release v1.0** プルリクエストを開きます。
1. **Merge pull request** をクリックします。
1. 約 20 秒待ってから、このページ（手順を実行しているページ）を更新します。[GitHub Actions](https://docs.github.com/en/actions) が自動的に次のステップに更新されます。

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
