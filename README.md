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
<<< 著者注: ステップ 6 >>>
前のステップを承認することから、このステップを開始します。
用語を定義し、docs.github.com へのリンクを追加します。
-->

## ステップ 6: リリースにホットフィックスをコミットする

_もうすぐ完了 :heart:_

ブランチを削除していないことに気づきましたか？これは意図的なものです。

リリースではミスが発生することがあります。その場合は、同じブランチで修正できるようにする必要があります。

リリースが確定したので、告白します。最近のアップデートのどこかでミスを犯し、バグを生じさせてしまいました。テキストの色を緑色に変更する代わりに、ゲームの背景全体を変更してしまいました。

_ヒント: GitHub Pages の更新には数分かかる場合があります。最近行った更新内容がすぐにページに反映されない場合があります。_

![image](https://user-images.githubusercontent.com/13326548/48045461-487dd800-e145-11e8-843c-b91a82213eb8.png)

「ホットフィックス」、つまりソフトウェアのバグを修正するための迅速な修正は、開発において通常行われるものです。アプリケーションのアップデートの説明には「バグ修正」としか書かれていないことがよくあります。

バージョンをリリースした後にバグが発生した場合は、対処する必要があります。作業を開始できるように、`hotfix-v1.0.1` ブランチと `fix-game-background` ブランチを既に作成しています。

ホットフィックスは、プルリクエストを作成してマージすることで提出します。

### :keyboard: アクティビティ: ホットフィックス プルリクエストの作成とマージ

1. `hotfix-v1.0.1` を `base` ブランチ、`fix-game-background` を `compare` ブランチとしてプルリクエストを作成します。
2. プルリクエストテンプレートに、変更内容を記述します。プルリクエストのタイトルは「Hotfix for broken game style」に設定できます。プルリクエストの本文には詳細な内容を含めることができます。以下に例を示します。
```
## Description:
- Fixed bug, set game background back to black
```
3. 変更内容を確認し、「**Create pull request**」をクリックします。
4. これをホットフィックス ブランチにマージしたいので、「**Merge pull request**」をクリックします。

これらの変更を `main` にもマージしたいので、ホットフィックスを含むプルリクエストを作成し、`main` にマージします。

### :keyboard: アクティビティ: リリースプルリクエストの作成

1. `main` を `base` ブランチ、`hotfix-v1.0.1` を `compare` ブランチとしてプルリクエストを作成します。
2. プルリクエストのタイトルが「Hotfix v1.0.1」であることを確認します。
3. プルリクエストの本文に詳細な内容を含めます。例を以下に示します。
```
## Description:
- Fixed bug introduced in last production release - set game background back to black
```
4. 変更内容を確認し、「**Create pull request**」をクリックします。
5. 「**Merge pull request**」をクリックします。
6. 約 20 秒待ってから、このページ（手順を実行しているページ）を更新します。[GitHub Actions](https://docs.github.com/en/actions) が自動的に次のステップに更新されます。

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
