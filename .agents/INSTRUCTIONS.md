# lifetime-support-website

{プロジェクトの説明を記載}

---

## 技術スタック

| 用途 | 技術 |
|------|------|
| （記載） | （記載） |


---

## .env ファイルの取り扱い禁止

`.env` ファイルの読み取り・書き込み・作成・編集・削除・コピー・移動など、一切の操作を**禁止**する。
`.env` ファイルの内容をユーザーに表示することも禁止。
環境変数の確認が必要な場合は、ユーザーに口頭で確認すること。

<!-- LIBRARY:start -->
## 📚 図書館（中央ナレッジ基盤）の参照ルール

`scripts` は一つの組織。知識の正本は中央図書館 `lts-knowledge/library/` に集約する。

- **情報を探すときは、まず図書館の蔵書目録 `lts-knowledge/library/catalog.generated.md` を検索する。**
- **調べた／作った再利用価値のある知識は、まず図書館に正本登録してから使う。** 各プロジェクトにはコピーを残さず「参照元パス＋取得日」を記録し、図書館を正本として呼び出す。
- 棚: `research/`(調査) `trainings/`(研修) `products-services/`(商品・サービス・価格)。
- 登録手順は `lts-knowledge/library/_meta/how-to-contribute.md`、規約は `_meta/schema.md`。
- 秘密情報・個人情報(restricted)は図書館に置かない。生メールは要約・匿名化のみ。
<!-- LIBRARY:end -->
