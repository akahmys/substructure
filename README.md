# Substructure

AIエージェントに、プロジェクトの初期準備（フォルダ作成・ルール設定・タスク整理）を実行させるための指示書です。

この指示書を直接AIに読ませるだけで、面倒なフォルダ作成からルール構築までを完了させます。

---

## 使用条件

Claude Codeなどの、フォルダやファイルを作成・操作できるAIエージェント専用です。

ChatGPTなど、ファイルを操作できないチャット画面だけのAIでは使えません。

---

## 開発の背景

巷にあふれる「AI超入門」を読んで、いちいちコピペしたり、フォルダをちまちま作成するのは、最も遠回りなAI活用法です。

---

## 使い方

作業用のフォルダを作成して、その直下でAIエージェントに次の指示をしてください。

```text
[ここに指示書URL] この通りに準備して。
```

自分の作業に合わせて変更したいことがあれば、AIエージェントに次の指示をしてください。

```text
[ここに変更したいこと] して。
```

ここまでの説明でわからないことがあれば、AIエージェントに次の質問をしてください。

```text
[ここにわからないこと] って何？どうすればいい？
```

### 指示書URL

用途に合わせて、以下のURLを使ってください。

* **基本バージョン**（開発・リサーチ・一般プロジェクト向け）
`https://raw.githubusercontent.com/akahmys/substructure/refs/heads/main/instructions/basic.md`

* **執筆・コンテンツ制作バージョン**（ブログ・小説・技術記事・ドキュメント作成向け）
`https://raw.githubusercontent.com/akahmys/substructure/refs/heads/main/instructions/writing.md`

* **ビジネス文章・ドキュメント作成バージョン**（稟議書・報告書・提案書・社内文書向け）
`https://raw.githubusercontent.com/akahmys/substructure/refs/heads/main/instructions/business-writing.md`

* **学術論文・研究レポート作成バージョン**（論文執筆、学会発表、大学のレポート作成向け）
`https://raw.githubusercontent.com/akahmys/substructure/refs/heads/main/instructions/academic.md`

* **Webフロントエンド開発バージョン**（React・Next.js・Vue・Vite等、UI/UX開発向け）
`https://raw.githubusercontent.com/akahmys/substructure/refs/heads/main/instructions/frontend.md`

* **上記に当てはまらない場合は、AIエージェントに次の指示をしてください。**
  
  ```text
  [ここに指示書URL] これを参考に [ここにプロジェクトの概要] 向けに準備して。
  ```

---

## 注意事項

使用に先立って、AIエージェントに次の質問をすることを推奨します。

```text
[ここに指示書URL] これ使っても大丈夫？
```

---

## ライセンス

[MIT License](LICENSE)
