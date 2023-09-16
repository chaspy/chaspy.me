---
title: "About"
draft: false
---

English follows Japanese.

# 基本情報と連絡先

|key|value|
|---|-----|
|Name|Takeshi Kondo|
|Email|take.she12[at]gmail.com|

# 職務要約

Software Engineer として 9年+, うち Site Reliability Engineer として 5年+、Engineering Manager としての経験が 2年+ あります。

On-Premise 環境でのハード・ネットワーク・ストレージの知識および Cloud 利用、それらを Software で制御する IaC や Container Orchestration 領域に強みがあります。

SRE として、Web Service の信頼性担保のためのObservability やIncident Response / Management の経験があります。SLI/SLO を100名規模の開発組織に導入し、Engineering だけでなく Culture として組織を推進する力があります。

Individual Contributor として、SRE / Platform Engineering 領域の Lead を担うことができます。そのために必要なツールや自動化のための Software Programming を行うことができます。

また、オンボーディングプロセスの導入および推進や、技術コミュニティの運営、カンファレンスの運営等、技術外での Culture Making 活動およびコミュニティ活動の実績と知見があります。

# 職務経歴

## [株式会社リクルート](https://www.recruit.co.jp/) (Oct. 2022 ~ Present)

### Senior Engineering Manager, StudySapuri K12 (Oct. 2023 ~ current)

スタディサプリ小中高の BtoC 領域の部長を担当。

### Engineering Manager, Site Reliability / Web Application Development (Oct. 2022 ~ Sep. 2023)

SRE として国内に展開する[スタディサプリ](https://studysapuri.jp) と海外に展開する [Quipper](https://www.quipper.com) の信頼性に関わる業務に従事。

加えて、スタディサプリ新中学講座の開発チームのマネジメントに従事。

### Engineering Manager, Site Reliability (Oct. 2021 ~ Sep. 2022)

SRE として国内に展開する[スタディサプリ](https://studysapuri.jp) と海外に展開する [Quipper](https://www.quipper.com) の信頼性に関わる業務に従事。

## [Quipper Limited](http://www.quipper.com) (Jun. 2018 ~ Sep. 2021)

### Lead Software Engineer, Site Reliability (Jun. 2020 ~ Sep. 2021)

SRE として国内に展開する[スタディサプリ](https://studysapuri.jp) と海外に展開する [Quipper](https://www.quipper.com) の信頼性に関わる業務に従事。

#### SRE Team の Lead Engineer としてTeam および開発組織の Lead

5-7名規模の SRE Team の Lead Engineer として、Team Member の業務遂行のための障壁を取り除き、Individual Contributor として成果を出しました。

#### Service の Alert Policy の再定義

Alert Policy もなく、都度反応しており、Noise となっていた状態から、Sevirity を定義、全166 のアラートを見直しました。

詳細は [Alerting Strategy for Self-Contained Team](https://speakerdeck.com/chaspy/alerting-strategy-for-self-contained-team) をご覧ください。

#### Argo Rollouts を用いた Progressive Delivery(Canary Release) の実現

Progressive Delivery の実践として、Kubernetes Native で導入が用意な Argo Rollouts を用い、Rails Upgrade などリスクの高い変更を段階的にリリースできる基盤作りに貢献しました。

#### Application Platform を Self-Hosted Kubernetes から Amazon EKS への移行

AWS 上に Self-Host していた Kubernetes Cluster を Amazon EKS へ移行しました。

詳細は [Self-Hosted Cluster から EKS への移行と Platform の Production Readiness](https://quipper.hatenablog.com/entry/2020/08/11/migration-to-eks) をご覧ください。

また、Cluster Upgrade に対しても ALB Weighted Target Groups を用いた Canary Reelase の仕組みを実現しました。

詳細は [ALB Weighted Target Groups による EKS Cluster の Canary Switching](https://quipper.hatenablog.com/entry/2020/10/07/eks-canary-switching) をご覧ください。

#### ドメイン固有データを利用した Scheduled Scaling

「定期テスト」という一斉にアクセスが発生するイベントに対して、サービスダウンを回避するために Kubernetes HPA External Metrics を利用した Scheduled Scaling を実現しました。

詳細は [Kubernetes HPA External Metrics を利用した Scheduled-Scaling](https://blog.studysapuri.jp/entry/2020/11/30/scheduled-scaling-with-hpa) をご覧ください。

以下の登壇資料でも解説しています。

- [想定外の負荷を乗り切ったオンライン教育サービスの裏側](https://speakerdeck.com/chaspy/how-we-overcame-the-covid-19-crisis)
- [HPA autoscaling/v2beta2 の機能解説と Datadog を利用した HPA External Metrics の活用事例](https://speakerdeck.com/chaspy/v2beta2-and-examples-of-using-hpa-external-metrics-with-datadog)

### Software Engineer, Site Reliability (Jun 2018 ~ Jun 2020)

SRE として国内に展開する[スタディサプリ](https://studysapuri.jp) と海外に展開する [Quipper](https://www.quipper.com) の信頼性に関わる業務に従事。

#### Microservices に転換する上での Production Readiness に関わるプロセス整備

組織の拡大を見越して、Monolith Application から Microservice Architecture に移行した後の、Production Readiness を担保するプロセスおよびカルチャーを作りました。具体的には以下のようなことを Lead しました。

- Service の Owner を決める・定義できる仕組み作り
- 新規サービス作成時のDesign Doc Review および Productoon Readiness Checklist の立ち上げ・メンテナンス
  - ref: [みんなでつくる Production Readiness](https://quipper.hatenablog.com/entry/2020/01/30/production-readiness-with-all)
- Cloud Infrastructure (Microservice が利用する RDS) を開発者が Self-Service で作成できる仕組み作り

#### SLI/SLO を計測、定義する文化を開発チームに導入

SRE の Core Concept である SLI/SLO を組織に導入しました。

詳細は [SRE NEXT 2020 で「SLO Review」というタイトルで登壇しました #srenext](https://quipper.hatenablog.com/entry/2020/01/30/slo-review) をご覧ください。

## [富士通株式会社](http://www.fujitsu.com/jp/) (Apl,2014 - Jun,2018)

### Software Engineer

#### [Public Cloud IaaS K5](https://jp.fujitsu.com/solutions/cloud/k5/)
* MariaDB Garela Cluster の停止時間を最小限にしながらの Major Version Upgrade 手法の提案
* OpenStack IaaS コンポーネント(Nova, Cinder, Glance, Keystone, and Heat) のバグ修正
* IaaS コンポーネントの無停止保守を行うツール開発
* OpenStack の CI/CD 環境の構築およびチームへの導入支援

#### [ServerView Resource Orchestrator](https://www.fujitsu.com/jp/products/software/infrastructure-software/infrastructure-software/ror/)
* ストレージコンポーネントの開発および修正

# 学歴

* [九州工業大学](http://www.kyutech.ac.jp/) 情報工学部 情報システム専攻 修了(Mar. 2014)
  * [次数情報を利用したリンク重要度推定およびネットワーク特性との相関調査 (情報ネットワーク)](https://ci.nii.ac.jp/naid/110009861196/)

# 資格

- 2020 Apl. [HashiCorp Certified: Terraform Associate](https://www.hashicorp.com/certification/terraform-associate/)
- 2020 Jan. [Site Reliability Engineering: Measuring and Managing Reliability](https://coursera.org/share/a5c7b848a3d2bbdbca851afeb1a77783)
- 2015 Jun. [情報セキュリティスペシャリスト](https://www.jitec.ipa.go.jp/1_11seido/sc_28.html)
- 2014 Dec. [ネットワークスペシャリスト](https://www.jitec.ipa.go.jp/1_11seido/nw.html)


---

Engineering Manager, Site Reliability at [Recruit Co., Ltd.](https://www.recruit.co.jp/) (Oct, 2021~), formaerly [Quipper](http://www.quipper.com) (Jul,2018〜).

I have six years of experience as a software engineer. Of that, I have two years of experience as a Site Reliability Engineer.

I'm good at implementing the necessary technologies and processes for organizations. I recently introduced a central theme, SLI/SLO, to both Japanese and global products and promoted it to a situation where developers can handle it themselves.

As a team and project lead, I can find a problem correctly and take the team forward through communication and facilitation.

I completed technical projects with a high degree of uncertainty and impact, such as migrating a Kubernetes Cluster from self-hosted to EKS and OS upgrades for Reverse Proxy.

I can communicate and discuss in English. As an SRE, I have introduced new technologies and processes to global product teams and supported their development productivity.

# Career

## [Recruit Co., Ltd.](https://www.recruit.co.jp/) (Oct, 2021~)

### Senior Engineering Manager, StudySapuri K12 (Oct, 2022 ~ Present)

* Responsible of Development Division for StudySapuri K12.

### Engineering Manager, Site Reliability (Oct, 2022 ~ Sep, 2023)

* Responsible of site reliability for [studysapuri.jp](https://studysapuri.jp) and [quipper.com](https://www.quipper.com)

* Responsible of Web Application Development for StudySapuri new junior high school course. 

### Engineering Manager, Site Reliability (Oct, 2021 ~ Sep. 2022)

* Responsible of site reliability for [studysapuri.jp](https://studysapuri.jp) and [quipper.com](https://www.quipper.com)

## [Quipper Limited](http://www.quipper.com) (Jun,2018〜)

### Lead Software Engineer, Site Reliability (Jun,2020〜)
* Responsible of site reliability for [studysapuri.jp](https://studysapuri.jp) and [quipper.com](https://www.quipper.com)
  * Lead SRE Team / Project
  * Define an alert policy and implement it in the service team
  * Introduce Progressive Delivery
  * Migrate application platform to AWS EKS

### Software Engineer, Site Reliability for Global Product (Jun 2018 ~ Jun 2020)

* Responsible for site reliability for [quipper.com](https://www.quipper.com)
  * Build an SLO review culture for all product teams.
  * Improve Circuit Breaker by introducing Envoy proxy
  * Manage Cloud Infrastructure with Code (Kubernetes manifest, Terraform DSL, Ansible Playbook, Nginx configuration, and CircleCI)
  * Build a standardized system for Microservices (Readiness Check, SLO, RDS self-service, Define service owner)
  * Improve site performance with Nginx Cache or CDN

## [Fujitsu Limited](http://www.fujitsu.com/jp/) (Apl,2014 - Jun,2018)

### Software Engineer

* [Public Cloud IaaS K5](https://jp.fujitsu.com/solutions/cloud/k5/)
  * Upgrade [MariaDB Garela Cluster](https://mariadb.com/kb/en/galera-cluster/) without an extended downtime
  * Bugfix and failure handling of IaaS configured with [OpenStack](https://www.openstack.org/) (Nova, Cinder, Glance, Keystone, and Heat)
  * Tool development for deploying without downtime ([Capistrano](https://capistranorb.com/))
  * Introduction and Enlightenment of CI/CD ([GitLab-ci](https://docs.gitlab.com/ee/ci/) and [OpenStack/Tempest](https://github.com/openstack/tempest)))
* [ServerView Resource Orchestrator](https://www.fujitsu.com/jp/products/software/infrastructure-software/infrastructure-software/ror/)
  * Resource Orchestrator is IaaS management software from Ruby on Rails
  * Enhance a new feature and Bug Fix

# Education

* Mar 2014 Master of Engineering in Information Technology
  * [Kyushu Institute of Technology](http://www.kyutech.ac.jp/)
  * [Estimation of Betweenness Centrality in terms of Links for Inferring Network Performance](https://ci.nii.ac.jp/naid/110009861196/)

# Certification

- 2020 Apl. [HashiCorp Certified: Terraform Associate](https://www.hashicorp.com/certification/terraform-associate/)
- 2020 Jan. [Site Reliability Engineering: Measuring and Managing Reliability](https://coursera.org/share/a5c7b848a3d2bbdbca851afeb1a77783)
- 2015 Jun. [Information Security Specialist Examination(SC)](https://www.jitec.ipa.go.jp/1_11seido/sc_28.html)
- 2014 Dec. [Network Specialist Examination(NW)](https://www.jitec.ipa.go.jp/1_11seido/nw.html)
