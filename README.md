# UK-GDS-DevOps-Manual

このドキュメントは [Devops — Government Service Design Manual](https://www.gov.uk/service-manual/operations/devops.html) の和訳です。

## 訳注

- ※bringing togetherで『恋人と同士にさせる』って意味もあるらしいですね


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
特に、DevOpsは下記についてがすべてです。

- culture (文化)
- automation (自働化)
- measurement (測定)
- sharing (共有)


## Culture (文化)


Devops needs a change in attitude so shared ownership and collaboration are the common working practices in building and managing a service. This culture change is especially important for established organisations.

Automation

Many business processes are ready to be automated. Automation removes manual, error-prone tasks – allowing people to concentrate on the quality of the service. Common areas that benefit from automation are:

release management (releasing software)
provisioning
configuration management
systems integration
monitoring
orchestration (the arrangement and maintenance of complex computer systems)
testing
Measurement

Data can be incredibly powerful for implementing change, especially when it’s used to get people from different groups involved in the quality of the end-to-end service delivery. Collecting information from different teams and being able to compare it across former silos can implement change on its own.

Sharing

People from different backgrounds (ie development and operations) often have different, but overlapping skill sets. Sharing between groups will spread an understanding of the different areas behind a successful service, so encourage it. Resolving issues will then be more about working together and not negotiating contracts.

Why Devops
The quality of your service will be compromised if teams can’t work together, specifically:

those who build and test software
those that run it in production
The root cause is often functional silos; when one group owns a specific area (say quality) it’s easy for other areas to assume that it’s no longer their concern.

This attitude is toxic, especially in areas such as:

quality
release management
performance
High quality digital services need to be able to adapt quickly to user needs, and this can only happen with close collaboration between different groups.

Make sure the groups in your team:

have a shared sense of ownership of the service
have a shared sense of the problem
develop a culture of making measurable improvements to how things work
Good habits
Devops isn’t a project management methodology, but use these good habits in your organisation. While not unique to Devops, they help with breaking down silos when used with the above principles:

cross-functional teams – make sure your teams are made up of people from different functions (this helps with the team owning the end-to-end quality of service and makes it easier to break down silos)
widely shared metrics – it’s important for everyone to know what ‘good’ looks like so share high and low level metrics as widely as possible as it builds understanding
automating repetitive tasks – use software development to automate tasks across the service as it:
encourages a better understanding of the whole service
frees up smart people from doing repetitive manual tasks
post-mortems – issues will happen so it’s critical that everyone across different teams learns from them; running post-mortems (an analysis session after an event) with people from different groups is a great way of spreading knowledge
regular releases – the capacity for releasing software is often limited in siloed organisations, because the responsibilities of the different parts of the release are often spread out across teams – getting to a point where you can release regularly (even many times a day) requires extreme collaboration and clever automation
Warning signs
Like agile, the term Devops is often used for marketing or promotional purposes. This leads to a few common usages, which aren’t necessarily in keeping with what’s been said here. Watch out for:

Devops tools (nearly always marketing)
a Devops team (in many cases this is just a new silo of skills and knowledge)
Devops as a job title (you wouldn’t call someone “an agile”)
Related guides in the Service Manual
Those interested in Devops are often also interested in:

Configuration Management
Monitoring
Release Management
Further reading
What Devops Means to Me
what is this Devops thing anyway?
what is Devops (and the wall of confusion)
there’s no such thing as a “Devops Team”
