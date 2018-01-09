<!-- $theme: gojiro -->
<!-- page_number: true -->

卒業研究発表
===

##### 宮治研究室
##### 上野 涼

---

#### 目次

- 背景・目的
- システム
- 実験
- 考察

---

#### 研究内容

**PCワークの進捗監視システム**

* 個人のPC上の作業を自動的に監視
* 作業内容を記録・報告を自動化

---

#### 背景

リモートワークの機会の増加

➡︎ <small>遠隔地の作業を監視する必要がある</small>

➡︎ <small>個人のスケジュール管理も重要である</small>

---

#### 目的

個人のPCワークの進捗管理と
行動監視を行い、生産性を向上させる
<br>

➡︎ 進捗監視システムを構築し、
　 有用性を検証する

---

#### システム

1. 作業予定を入力
2. 作業をする
3. 作業状況を監視・記録
4. 記録された情報を管理者に通知

---

#### 作業予定の入力

作業者が自身の作業の予定を立てる

* タスクの分割
* 作業日時を入力

---

#### 作業をする

予定していた時刻に作業を実施する


* 作業中はアプリを常に起動しておく
* 予定時間が過ぎてもアプリを
起動しなかった場合、作業者に通知

---

#### 作業の実施

システムによって監視される

* <small>作業予定時間に作業を開始しているか</small>
* <small>作業に不要なサービスを利用していないか</small>

---

#### サービスの検出

作業中の画面からサービスを検出

* <small>定期的に画面のスクリーンショットを取得</small>
* <small>画像を解析してサービスを検出</small>
* <small>不要なサービスかどうか判定</small>

---

#### 管理者に通知

定時にチャットサービスを通じて
管理者に作業記録を通知する

* 作業時間
* 作業内容
* 不要なサービスの検出記録

---

# デモ

---

#### 実験

###### 対象

宮治研究室の学生及び教員

###### 方法

40日間、学生の論文の執筆を監視

➡︎ アンケートにてシステムを評価


---

#### 結果

<br>

* 作業時間を記録、報告までを自動化
* 予定に従って行動を促す効果がある
* 監督者も作業の現状を把握できる

---

#### 課題

個人の予定を正確に
システムに反映させることが困難

<br>
➡︎ 予定管理の入力に手間がかかる

➡︎ **ユーザの負担を軽減する必要がある**