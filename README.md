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
<<< 作成者メモ: コース開始 >>>
開始ボタン、Actions の所要時間に関するメモ、そして受講者にこのコースを受講する理由を伝えます。
-->

## ようこそ

[GitHub フロー](https://guides.github.com/introduction/flow/) を基盤として、リリースベースのワークフローを作成しましょう。チームでリリースベースのワークフローを使用すると、GitHub を利用することで、プロジェクトのデプロイ可能なイテレーションを容易に共同作業でき、パッケージ化してより幅広いユーザーがダウンロードして使用できるようにすることができます。

GitHub リリースを使用すると、チームはプロジェクトの履歴の特定の時点に基づいてソフトウェアをパッケージ化し、ユーザーに提供できます。

- **対象者**：開発者、DevOps エンジニア、IT 運用担当者、マネージャー、およびチーム。
- **学習内容**：リリースベースのワークフローの実施方法。
- **構築するもの**：タグ、リリース、リリースノートを作成します。
- **前提条件**: ブランチ、コミット、プルリクエストについて学習する必要がある場合は、まず[GitHub 入門](https://github.com/kuboctopus/introduction-to-github)を受講してください。
- **所要時間**: このコースは 1 時間以内で修了できます。

このコースでは、次の内容を学習します。

1. ベータリリースを作成する
2. リリースに機能を追加する
3. リリースプルリクエストを開く
4. リリースノートを追加してマージする
5. リリースを確定する
6. ホットフィックスをコミットする
7. ホットフィックスリリースを作成する

### このコースの開始方法

<!-- コースを開始するには、JavaScript で次のコマンドを実行します:
'https://github.com/new?' + new URLSearchParams({
template_owner: 'kuboctopus',
template_name: 'release-based-workflow',
owner: '@me',
name: 'skills-release-based-workflow',
description: 'My clone repository',
visibility: 'public',
}).toString()
-->

[![start-course](https://user-images.githubusercontent.com/1221423/235727646-4a590299-ffe5-480d-8cd5-8194ea184546.svg)](https://github.com/new?template_owner=kuboctopus&template_name=release-based-workflow&owner=%40me&name=skills-release-based-workflow&description=My+clone+repository&visibility=public)

1. **「Start cource」** を右クリックし、リンクを新しいタブで開きます。
2. 新しいタブでは、ほとんどのプロンプトが自動的に入力されます。
   - オーナーとして、個人アカウントまたはリポジトリをホストする組織を選択します。
   - プライベートリポジトリは [Actions の分単位での課金](https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions) が発生するため、パブリックリポジトリを作成することをお勧めします。
   - 下にスクロールし、フォームの下部にある **「リポジトリを作成」** ボタンをクリックします。
3. 新しいリポジトリが作成されたら、約 20 秒待ってからページを更新します。新しいリポジトリの README に記載されている手順に従ってください。

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
