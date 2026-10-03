# Tamang Amish（タマン アミス）

横浜でITヘルプデスクとテクニカルサポートをしています。ネパール出身で、2018年から日本に住んでいます。

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?logo=playwright&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?logo=pytest&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?logo=postman&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)

---

## いまの仕事

社内から来る「アプリが開かない」「印刷できない」といった問い合わせに、最初に対応する役割です。

申告を受けたら、まず自分の端末で同じことが起きるか試します。いつ、どの端末で、どの操作をしたときに起きるのか。そこまで絞ってから、再現手順と環境を書いて担当者に渡します。自分で直せるものは直し、直せないものは調べた内容をつけてエスカレーションします。

問い合わせ対応のほかに、PC・タブレット・スマートフォンのキッティングと引き渡し前の動作確認、基幹システム（OBIC7）のデータ移行支援と出力帳票の確認、IT資産管理、購買事務を担当しています。

その前は携帯ショップで端末の不具合対応を1年半やりました。お客様に専門用語を使わずに説明する仕事です。さらにその前は製造業で、出荷前検査と品質管理を2年9か月。15人のチームリーダーもしていました。

業種はばらばらですが、やっていることは似ています。基準があって、それに合っているかを確認して、結果を記録して次の人に渡す。ずっとこれをやってきました。

## 職歴

| 期間 | 仕事 | 内容 |
|---|---|---|
| 2025年6月〜現在 | ITヘルプデスク・テクニカルサポート | 一次問い合わせ対応、不具合の再現と切り分け、インシデント報告、キッティング、OBIC7のデータ移行支援、IT資産管理、購買事務 |
| 2023年12月〜2025年5月 | テクニカルサポート（auショップ） | 端末不具合の再現と切り分け、初期設定とデータ移行、手順書と研修資料の作成 |
| 2021年4月〜2023年12月 | 品質管理・出荷前検査／チームリーダー | 検査基準に沿った確認と記録、不良の報告、15名の作業割り当てと新人教育、作業手順の統一 |

## 業務外で作ったもの

ソフトウェアテストは仕事で扱う機会がありません。なので題材を自分で決めて、設計から実行まで一通り作りました。4つあります。

| | リポジトリ | 内容 | 結果 |
|---|---|---|---|
| 01 | [01-eccube-manual-qa](https://github.com/amishanita/01-eccube-manual-qa) | EC-CUBE 4.2.3 の手動テスト設計と不具合報告 | 49機能を洗い出し、27要件に整理、テストケース40件 |
| 02 | [02-saucedemo-playwright-python](https://github.com/amishanita/02-saucedemo-playwright-python) | Playwright と pytest によるUI自動テスト | 31実行、30成功・1スキップ・0失敗 |
| 03 | [03-restful-booker-api-automation](https://github.com/amishanita/03-restful-booker-api-automation) | REST API の仕様と実挙動の突き合わせ | 25ケース、仕様と違う箇所を5件検出。curlで再現手順を記録 |
| 04 | [04-saucedemo-ci-cd-qa](https://github.com/amishanita/04-saucedemo-ci-cd-qa) | GitHub Actions での自動実行 | 15ケース全成功。PR時・マージ時・夜間の3種類 |

4つは別々の課題ではなく、順番につながっています。

01で、何を確認して何を確認しないかを決めました。全部の組み合わせは試せないので、落とした範囲とその理由も残しています。02では、そのうち毎回同じことを繰り返す部分を自動化しました。画面の定義とテストの手順を分けて、UIが変わったときに直す場所が1か所で済む形にしています。03では画面の裏側を見ました。APIのドキュメントに書いてある内容と、実際に返ってくるレスポンスを突き合わせています。04で、ここまでを人が実行しなくても回るようにしました。プルリクエストのときは短く、夜間は全部、という具合に実行範囲を変えています。

## 使っているもの

**テスト**
Playwright / pytest / Postman / curl / requests / Selenium（学習中）

**言語**
Python / SQL（PostgreSQL）/ JavaScript / HTML / CSS / Bash / YAML

**バージョン管理・CI**
Git / GitHub / GitHub Actions / Docker（基礎）

**業務システム**
OBIC7 / kintone / Kizuku / Spirit / Microsoft 365 / Box / DocuWorks / Jira / Excel（VLOOKUP、ピボットテーブル、VBA）

## 資格・語学

- BJT ビジネス日本語能力テスト 420点
- JPT（Japanese Proficiency Test）620点
- 普通自動車第一種運転免許
- JSTQB Foundation Level　2026年11月11日 受験予定
- 日本語能力試験 N1　2026年12月6日 受験予定

日本語（ビジネスレベル）、英語（中級）、ネパール語（母語）、ヒンディー語（日常会話）

## 探している仕事

QAエンジニア、テストエンジニア、ITヘルプデスク、テクニカルサポート、社内SE・情報システム、IT事務。

自社の中で仕事が完結する会社を探しています。作って終わりではなく、運用まで見られる環境で長く働きたいと思っています。

勤務地は神奈川県、東京都、千葉県、埼玉県。フルリモートも可能です。2026年12月から勤務できます。

[LinkedIn](https://www.linkedin.com/in/tamang-amish-669289250)　|　amishmoktan2019@gmail.com

---
---

# English

# Tamang Amish

I work as an IT helpdesk and technical support engineer in Yokohama, Japan. I'm from Nepal and have lived in Japan since 2018.

## What I do now

I'm the first person people reach when something at work stops working. "The app won't open." "I can't print."

When a report comes in, I try to make it happen on my own machine first. When it started, which device, which action. Once I've narrowed it down, I write up the steps and the environment and hand it over. What I can fix, I fix. What I can't, I escalate with what I've already found.

Alongside that I handle device setup for PCs, tablets and phones, including the checks before they go out. I support data migration for our ERP (OBIC7) and verify the documents it generates. I also manage IT assets and handle purchasing paperwork.

Before this I spent a year and a half at a mobile phone shop, diagnosing handset problems and explaining them to customers without using technical words. Before that, two years and nine months in manufacturing, doing pre-shipment inspection and quality control. I led a team of 15 there.

Different industries, similar work. There's a standard, you check whether the thing matches it, you write down what you found, and you pass it on. That's what I've been doing all along.

## Experience

| Period | Role | Work |
|---|---|---|
| Jun 2025 – present | IT Helpdesk / Technical Support | First-line support, reproducing and isolating faults, incident reports, device kitting, ERP (OBIC7) data migration, IT asset management, purchasing admin |
| Dec 2023 – May 2025 | Technical Support, au mobile store | Reproducing handset faults, device setup and data transfer, writing store procedures and training material |
| Apr 2021 – Dec 2023 | QC & Pre-shipment Inspection / Team Leader | Inspection against written criteria, defect recording and reporting, led 15 people, standardised the inspection procedure |

## Projects I built on my own time

Software testing isn't part of my job, so I picked my own subjects and built four projects end to end.

| | Repository | What it is | Result |
|---|---|---|---|
| 01 | [01-eccube-manual-qa](https://github.com/amishanita/01-eccube-manual-qa) | Manual test design and defect reports for EC-CUBE 4.2.3 | 49 features inventoried, 27 requirements derived, 40 test cases |
| 02 | [02-saucedemo-playwright-python](https://github.com/amishanita/02-saucedemo-playwright-python) | UI automation with Playwright and pytest | 31 runs, 30 passed, 1 intentional skip, 0 failed |
| 03 | [03-restful-booker-api-automation](https://github.com/amishanita/03-restful-booker-api-automation) | REST API tested against its own documentation | 25 cases, 5 discrepancies found, each reproducible with curl |
| 04 | [04-saucedemo-ci-cd-qa](https://github.com/amishanita/04-saucedemo-ci-cd-qa) | Running the suite on GitHub Actions | 15 cases passing, across PR, merge and nightly workflows |

They follow on from each other.

In 01 I decided what to test and what to leave out. You can't try every combination, so I wrote down what I skipped and why. In 02 I automated the parts that get repeated every time, keeping the selectors in page classes so there's one place to fix when the UI moves. In 03 I went underneath the interface and compared what the API documentation promises with what the service actually returns. In 04 I made all of it run without anyone pressing a button, with a short run on pull requests and the full suite overnight.

## Tools

**Testing** Playwright, pytest, Postman, curl, requests, Selenium (learning)
**Languages** Python, SQL (PostgreSQL), JavaScript, HTML, CSS, Bash, YAML
**Version control and CI** Git, GitHub, GitHub Actions, Docker (basic)
**Business systems** OBIC7, kintone, Microsoft 365, Box, DocuWorks, Jira, Excel

## Certifications and languages

- BJT Business Japanese Proficiency Test, 420
- JPT, 620
- Japanese driving licence
- JSTQB Foundation Level, sitting 11 November 2026
- JLPT N1, sitting 6 December 2026

Japanese (business level), English (intermediate), Nepali (native), Hindi (conversational)

## What I'm looking for

QA engineer, test engineer, IT helpdesk, technical support, internal IT, or IT administration.

I'm looking for a company that keeps its work in house, where I can stay with something past the point where it ships and see how it holds up in use.

Kanagawa, Tokyo, Chiba or Saitama. Fully remote also works. Available from December 2026.

[LinkedIn](https://www.linkedin.com/in/tamang-amish-669289250)　|　amishmoktan2019@gmail.com
