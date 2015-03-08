このドキュメントは [Devops — Government Service Design Manual](https://www.gov.uk/service-manual/operations/devops.html) の和訳です。

# UK-GDS-DevOps-Manual

## 訳注

- ※bringing togetherで『恋人同士にさせる』って意味もあるらしいですね。原文には ***bringing development and operations together*** ってありました。

## DevOps

開発と運用をまとめる。

DevOpsは、大規模組織によって一般的に行なわれている間違いに対する文化的、専門的な運動です。  
組織はいかのような単位で断絶していることがよくあります。

- 開発
- QA
- 運用

これらの単位は、極端だとこんな風になっているかもしれません。

- 違う場所にいる
- 違う組織で働いている
- 全く違う管理構造の下にいる

これらの単位、もしくは個人のインセンティブ間にあるコミュニケーションのコストは、価値提供の遅延と、相互のプロセスの巨大化を導きます。  
DevOpsはこの間違いを指摘しています。DevOpsは方法論やフレームワークではありません。この間違った関係を壊す意欲と原則の集まりです。  
特に、DevOpsは下記の4つの項目がすべてです。。

- culture (文化)
- automation (自働化)
- measurement (測定)
- sharing (共有)


## Culture (文化)

DevOpsはオーナーシップを共有し、サービスの構築から管理までを共に行うコラボレーションする変化を必要としています。  
この文化の変化は、組織を確立するために特に重要です。


## Automation (自働化)

多くのビジネスプロセスは、自働化される予定です。自働化はマニュアルや、間違いを引き起こすタスクをなくし、私達がサービス品質に注力することを許します。  
自働化は、一般的な領域で役立ちます。

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
- [幅広いメトリクスの共有](https://www.gov.uk/service-manual/measurement) - it’s important for everyone to know what ‘good’ looks like so share high and low level metrics as widely as possible as it builds understanding
- 反復タスクの自働化 - use software development to automate tasks across the service as it:
 - encourages a better understanding of the whole service
 - frees up smart people from doing repetitive manual tasks
- [振り返り] - issues will happen so it’s critical that everyone across different teams learns from them; running post-mortems (an analysis session after an event) with people from different groups is a great way of spreading knowledge
- [定期的なリリース](https://www.gov.uk/service-manual/making-software/release-strategies) - the capacity for releasing software is often limited in siloed organisations, because the responsibilities of the different parts of the release are often spread out across teams – getting to a point where you can release regularly (even many times a day) requires extreme collaboration and clever automation


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
