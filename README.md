このドキュメントは [Devops — Government Service Design Manual](https://www.gov.uk/service-manual/operations/devops.html) の和訳です。

# UK-GDS-DevOps-Manual

## 訳注

- ※bringing togetherで『恋人同士にさせる』って意味もあるらしいですね。原文には ***bringing development and operations together*** ってありました。

## DevOps

開発と運用をまとめる。

DevOpsは、大規模組織によって一般的に行なわれている間違いに対する文化的、専門的な運動です。  
組織は下記単位で断絶していることがよくあります。

- 開発
- QA
- 運用

これらの単位は、極端だとこんな風になっているかもしれません。

- 違う場所にいる
- 違う組織で働いている
- 全く違う管理構造の下にいる

これらの単位の、もしくは個人のインセンティブ間のコミュニケーション・コストは、価値提供の遅延と、相互のプロセスの巨大化を導きます。  
DevOpsはこの間違いを指摘しています。DevOpsは方法論やフレームワークではありません。この間違った関係を壊す意欲と原則の集まりです。  

DevOpsは下記の4つの項目がすべてです。

- culture (文化)
- automation (自働化)
- measurement (測定)
- sharing (共有)


## Culture (文化)

DevOpsはオーナーシップを共有し、サービスの構築から管理までを共に行うコラボレーションする変化を必要としています。  
文化の変化は、組織を確立するために特に重要です。


## Automation (自働化)

多くのビジネスプロセスは、自働化されるのを待っています。  
自働化はマニュアルや、間違いを引き起こすタスクをなくし、私達がサービス品質に注力することを許します。  
自働化は、一般的に下記領域で役立ちます。

- リリース管理 (ソフトウェアをリリースする)
- プロビジョニング
- 設定管理
- システム構築
- 監視
- オーケストレーション (複雑なコンピュータシステムのメンテナンス)
- テスト
- 測定

データは驚くほど強烈な変化をもたらすことができます。エンド・ツー・エンドなサービス・デリバリー品質に関係する、異なるグループであることに慣れた人々に取っては特にです。  
互いのチームから情報を集め、相互間で比較することができることによって変化を実行することができるようになるのです。


## Sharing (共有)

異なる背景（例えば開発と運用）を持つ人々は、異なった、けれどオーバーラップしたスキルセットを持っています。  
グループ間で共有することは、サービスの成功の裏にある異なった領域の理解を広げます。  
問題を解決することとは、共に働くことであり、契約を協議することではないのです。


## 何故DevOpsか？

もしチームが共に働く事ができないのであれば、あなたのサービスの品質は損なわれていくことでしょう。

- 誰がビルドして、テストするのか
- 誰がプロダクション環境で稼働させるのか

根本的な原因は、隔てられた機能部門にあります。  1つのグループが特別な領域（たとえば品質とか）を持つとき、他の領域は、彼らにとって考えることはないと決めてしまいがちです。

この考え方は猛毒です。下記のような領域を持つ場合は特にです。

- 品質
- リリース管理
- パフォーマンス

高品質なディジタル・サービスはユーザのニーズに素早く適応することが必要であり、これは異なるグループ間で密なコラボレーションを発揮することによってのみ実現できます。

あなたのチームで、確かめてください。

- サービスのオーナーシップは共有されていますか？
- 問題は共有されていますか？
- 改善がもたらされる働き方の文化を醸成していますか？


## Good habits (良い習慣)

DevOpsはプロジェクト管理の方法論ではありませんが、あなたの組織にとって良い習慣として下記を使うことができます。  
DevOpsとして独特なことをするではなく、部署間の隔たりをぶち壊したいときに、それを手伝ってくれるものです。

- [クロス・ファンクショナル・チーム](https://www.gov.uk/service-manual/the-team) - 互いに異なる職能を持った人々によって成り立ちます。(これはエンド・ツー・エンドなサービス品質をチームが認識することを助け、部署間の隔たりをを壊しやすくします)
- [幅広いメトリクスの共有](https://www.gov.uk/service-manual/measurement) - 全員が理解をして、低レベルから高レベルのメトリクスを可能な限り幅広く共有され、何が「よいこと」か知ることは重要です。
- 反復タスクの自働化 - サービスをまたがって、ソフトウェア開発のタスク自働化を行おう
 - 全サービスのより良い理解を促します
 - 繰り返されるマニュアルタスクから、人々を自由にします
- [振り返り] - 問題は起こるものなので、異なるチーム同士でそこから学ぶことが重要です。異なるグループで振り返りを（イベント後の分析セッションで）行うことは、知識を広めるよい方法です。
- [定期的なリリース](https://www.gov.uk/service-manual/making-software/release-strategies) - ソフトウェアリリースのキャパシティは、よく組織の隔たりによって制限されます。何故ならリリース内容の様々な責任は、チームにまたがって広がっているからです。 定期的にリリースすることができるようになるには、賢い自働化と極度のコラボレーションが必要です。


## こんなサインには気をつけて

Like agile, the term Devops is often used for marketing or promotional purposes. This leads to a few common usages, which aren’t necessarily in keeping with what’s been said here. Watch out for:

- Devops tools (nearly always marketing)
- a Devops team (in many cases this is just a new silo of skills and knowledge)
- Devops as a job title (you wouldn’t call someone “an agile”)


## サービスマニュアルの関連ガイド

Those interested in Devops are often also interested in:

- [Configuration Management](https://www.gov.uk/service-manual/making-software/configuration-management.html)
- [Monitoring](https://www.gov.uk/service-manual/operations/monitoring.html)
- [Release Management](https://www.gov.uk/service-manual/making-software/release-strategies.html)


## さらに読んでみよう

- [What Devops Means to Me](https://www.chef.io/blog/2010/07/16/what-devops-means-to-me/)
- [what is this Devops thing anyway?](http://www.jedi.be/blog/2010/02/12/what-is-this-devops-thing-anyway/)
- [what is Devops (and the wall of confusion)](http://dev2ops.org/2010/02/what-is-devops/)
- [there’s no such thing as a “Devops Team”](http://continuousdelivery.com/2012/10/theres-no-such-thing-as-a-devops-team/)
