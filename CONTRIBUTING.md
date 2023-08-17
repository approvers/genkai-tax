# genkai-tax: リポジトリ運用

このドキュメントでは, approvers/genkai-tax の運用方法について説明します.

> **Warning**
>
> このドキュメントは **神・治安部隊・限界財務省のメンバー** 向けに書かれています.
> 一般の方は, [README](../README.md) または [納税者向けドキュメント](./docs/README.md) をご覧ください.

----

- [genkai-tax: リポジトリ運用](#genkai-tax-リポジトリ運用)
  - [権限管理](#権限管理)
    - [コードオーナー](#コードオーナー)
    - [納税者向けドキュメント](#納税者向けドキュメント)
    - [Discussions](#discussions)

## 権限管理

> **Note**
>
> このリポジトリの権限管理は Discord の権限とは関係ありません.

approvers/genkai-tax は GitHub Team 機能を使い, 権限を管理しています.

リポジトリ全体の権限(`Admin`)は **[カスみが関][ks]に所属するメンバー**と [カスみが関][ks] の配下に在する **[限界財務省][zaimusho] のメンバー**に対して与えられます.

> **Note**
>
> 神・治安部隊は, 限界財務省のメンバーではありませんがOrg全体の権限を所有するため自動的に `Admin` ロールが割り当てられます.

### コードオーナー

`genkai-tax` はすべてのファイルに対して適切にコードオーナーが定義されています.

| ファイル | コードオーナー |
| --- | --- |
| `README.md` | [限界財務省][zaimusho] |
| `CONTRIBUTING.md` | [限界財務省][zaimusho] |
| `.github/workflows/` 配下 | [@m1sk9][m1sk9] |
| `accounts/` 配下 (会計報告) | [限界財務省][zaimusho]* |
| `docs/` 配下 (ドキュメント) | [限界財務省][zaimusho] |

これらのファイルに対してプルリクエストを発行した際は, コードオーナーの承認(Approve)が必要です.

`*`: 会計報告を行うのは [@Colk-tech][Colk-tech] のため, GitHub の仕様上レビュワーには含まれません.

### 納税者向けドキュメント

納税者向けドキュメントは, 限界財務省のメンバーが編集することができます. その他のメンバー(これは外部貢献者も含まれます.) も編集することは可能ですが、[コードオーナー](#コードオーナー) からのレビューと承認が必要です.

ドキュメントは `docs/` 配下に配置されています. これらのドキュメントは GitHub 上で閲覧出来る他、 GitHub Pages でのデプロイにより [tax.approvers.dev](https://tax.approvers.dev) でも閲覧することができます.

### Discussions

当リポジトリでは [GitHub Discussions](https://docs.github.com/ja/discussions) を使用しています.

Discussions では会計報告・限界税に関する質問や要望を受け付けています.

提出時は適切なカテゴリーを選択し, 作成してください。

> **Warning**
>
> [GitHub Discussions](https://docs.github.com/ja/discussions) 内での議論は, 外部に公開されています.
> 個別で [限界財務省][zaimusho] に連絡する必要がある場合は, Discord で行ってください.

[m1sk9]: https://github.com/m1sk9
[Colk-tech]: https://github.com/Colk-tech
[ks]: https://github.com/orgs/approvers/teams/ks
[zaimusho]: https://github.com/orgs/approvers/teams/ministry-of-finance
