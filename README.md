# specs

💡 **SDD（仕様駆動開発）に基づくアイデアの堆積場**

本リポジトリは、[@Ningensei848](https://github.com/Ningensei848) が思いついた様々なシステムのアーキテクチャやツールのコンセプトを、仕様書（Specifications）として具現化し、並列に蓄積・公開していく場所です。

ここに格納されるドキュメントは、すべて **仕様駆動開発（SDD: Spec Driven Development）** の原則に則り、GitHub公式の [Spec-Kit](https://github.com/github/spec-kit) をGeminiに読み込ませて、AIと二人三脚で策定しています。


## 🎯 Philosophy and Mission Statement

ここは言うなれば、未実装のアイデアたちが層をなす「堆積場」です。

単なるメモ書きに留めず、AIエージェントや人間がいつでも実装に移行できるレベルまで、厳密に関心を分離して構造化した仕様書パッケージとしてディレクトリごとに独立して配置していきます。


### 🚀 Feel free to implement or reuse it 

> I'd be really glad if you did !

- 「アイデアはあるが、自分で実装する時間が足りない」
- 「誰かが作ってくれたら自分も使いたい」

そんな思いから、ここにある仕様書をベースに、各人が各々のシステムを自由に作成・実装することは**大歓迎**としています。
ライセンスの許す限り、Forkするもよし、そのまま実装して公開するもよしです。
ここに眠るアイデアを形にしてくれる親切な開発者が現れることを、心から楽しみにしています。


## 🗺️ Projects

今後、新しいアイデアが生まれるたびに、ルート直下に独立したディレクトリとその仕様書群が追加されていきます。

現在展開中、および今後堆積予定のプロジェクトのナビゲーションです。

| プロジェクト（ディレクトリ） | 概要・ステータス |
| :--- | :--- |
| **[🧿 kaname](./kaname-architect/)** | **【設計完了】日本のサイバーセキュリティインテリジェンス自動収集システム**<br>GCP（Cloud Run Jobs / Scheduler）を用いた完全サーバーレス環境下で、2つのLLM（提案/査読）がマルチエージェントとして協調し、自律的にクローリング・PR生成・コードレビュー・ `main` へのマージ・Discord通知までを完結させるナレッジオーケストレーションシステム。 |
| **📂 `[Next Project].md`** | *Loading Next Idea...* （ここに新しいSDD仕様書パッケージが随時追加されていきます） |

各ディレクトリ内には、そのプロジェクトの背景、機能要件、データモデル、タスクリストなどが自己完結した形でパッケージングされています。
興味のあるディレクトリを覗いてみてください。


## 📚 参考文献・関連エコシステム

仕様の策定にあたり、以下のエコシステムや思想に多大なる影響を受けています。

- **[Spec-Kit](https://github.com/github/spec-kit)** - GitHub公式の仕様駆動開発プロンプトキット
- **[LLM Wiki](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f)** (by Andrej Karpathy) - LLMによる構造化Wikiの思想


## Author

[![Twitter is what's happening in the world and what people are talking about right now.](https://img.shields.io/badge/@Ningensei848-%231DA1F2.svg?&style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/Ningensei848)

[![](https://img.shields.io/badge/k.kubokawa@klis.tsukuba.ac.jp-%23757575.svg?&style=for-the-badge&logo=gmail&logoColor=EA4335)](mailto:k.kubokawa@klis.tsukuba.ac.jp)

## License

_This software is released under the [MIT License](LICENSE)._
