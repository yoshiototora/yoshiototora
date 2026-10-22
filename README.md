<div align="center">

# Koki Yoshioka｜吉岡 晃基

長崎大学大学院 総合生産科学研究科 修士1年<br>
コミュニケーションメディア研究室 — 360°3D映像の合成と視差量の最適化

<br>

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yoshiototora)
[![Qiita](https://img.shields.io/badge/Qiita-55C500?style=for-the-badge&logo=qiita&logoColor=white)](https://qiita.com/yoshiototora)
[![App Store](https://img.shields.io/badge/HabitSpark-0D96F6?style=for-the-badge&logo=appstore&logoColor=white)](https://apps.apple.com/jp/app/habitspark/id6762178668)

</div>

<br>

Web・iOSアプリ開発、3DCG映像制作、ハッカソンに取り組んでいます。
小中学生向けのMinecraft・Blender指導や、島根での販路開拓インターンも経験しました。

<table>
  <tr>
    <td align="center" width="25%">
      <b>最優秀賞</b><br>
      <sub>警察庁 サイバー防犯ボランティア<br>広報啓発コンテスト</sub>
    </td>
    <td align="center" width="25%">
      <b>優秀賞</b><br>
      <sub>SPAJAM2026<br>九州大会</sub>
    </td>
    <td align="center" width="25%">
      <b>App Store 公開</b><br>
      <sub>習慣化アプリ<br>HabitSpark</sub>
    </td>
    <td align="center" width="25%">
      <b>6店舗と契約</b><br>
      <sub>生マッコリの<br>販路開拓インターン</sub>
    </td>
  </tr>
</table>

## Tech Stack

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=py,pytorch,opencv,swift,react,nextjs,ts,kotlin,blender,pr,git,github&perline=12" alt="Python, PyTorch, OpenCV, Swift, React, Next.js, TypeScript, Kotlin, Blender, Premiere Pro, Git, GitHub" />
  </a>
</p>

## 研究・制作

### 360°3D映像の研究

<sub>卒業研究〜修士研究 · コミュニケーションメディア研究室</sub>

3台の360°カメラの映像から、VRで視聴できる立体映像を生成しています。
つなぎ目で人物の形が崩れる問題に対し、AIによる深度推定で前景と背景を分けて合成する手法を研究しています。カメラの固定器具も3Dプリンターで設計・制作しました。

評価実験では、つなぎ目の見え方と映像の安定性が改善しました。視差量も比較し、今回の実験では **55mm相当の条件が65mm相当よりVR酔いを抑える** 結果になりました。

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Depth Anything V2](https://img.shields.io/badge/Depth_Anything_V2-444444?style=flat-square)

| リポジトリ | 内容 |
| :-- | :-- |
| [360-video-synthesis-v2](https://github.com/yoshiototora/360-video-synthesis-v2) | 映像合成 v2 |
| [360-video-synthesis-v1](https://github.com/yoshiototora/360-video-synthesis-v1) | 卒業研究 v1 |
| [vr-ssq-evaluation](https://github.com/yoshiototora/vr-ssq-evaluation) | SSQによるVR酔いの分析 |
| [Quest3S_VideoTest](https://github.com/yoshiototora/Quest3S_VideoTest) | Meta Questでの視聴検証 |

### HabitSpark

<sub>個人開発 · 企画／UI設計／実装／公開</sub>

目標を月・週・日に分けて管理する習慣化アプリです。

KPTによる振り返りと、改善策を翌日のタスクに反映する機能を実装しました。レビューを受けて未完了タスクの引き継ぎ機能も追加し、3日連続で未完了のタスクはProblemに戻して見直せる設計にしています。

![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0D96F6?style=flat-square&logo=swift&logoColor=white)
![SwiftData](https://img.shields.io/badge/SwiftData-444444?style=flat-square&logo=swift&logoColor=white)

[App Store](https://apps.apple.com/jp/app/habitspark/id6762178668) · [コード](https://github.com/yoshiototora/GoalTracker)

### オープンキャンパスの案内Webアプリ

<sub>大学の有志4人 · 企画提案／フロントエンド担当</sub>

AIやロボットなどのタグから、展示とその場所を探せる案内アプリです。運営側には、Excelの展示データを貼り付けて情報を更新できる管理機能を用意しました。

活動は「広報委員会0期生」として認定され、当日の様子をまとめた特設サイトも大学公式ホームページに掲載されました。

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

### フィッシング詐欺の啓発アニメーション

<sub>有志3人 · ストーリー／3DCG担当</sub>

> **警察庁主催 令和7年度サイバー防犯ボランティア広報啓発コンテスト<br>フィッシング対策部門 最優秀賞（サイバー警察局長賞）**

釣りをする猫を詐欺師、宅配を待つ犬を被害者に見立て、フィッシング詐欺の手口と注意点を伝える動画です。作中の偽サイトは、実際にWebページを制作して再現しました。

<a href="https://www.youtube.com/watch?v=2JKH-jF41Kk">
  <img src="https://img.youtube.com/vi/2JKH-jF41Kk/hqdefault.jpg" width="420" alt="フィッシング詐欺の啓発アニメーション（YouTube）" />
</a>

![Blender](https://img.shields.io/badge/Blender-E87D0D?style=flat-square&logo=blender&logoColor=white)
![Premiere Pro](https://img.shields.io/badge/Premiere_Pro-00005B?style=flat-square)

[動画を見る](https://www.youtube.com/watch?v=2JKH-jF41Kk) · [警察庁](https://www.npa.go.jp/bureau/cyber/koho/news/2026318contest.html) · [大学の記事](https://www.nagasaki-u.ac.jp/ja/news/news4988.html)

## その他の活動

### SPAJAM2026 九州大会 — 優秀賞

<sub>チーム開発 · アイデア出し／企画検討</sub>

食事写真を撮るとキャラクターが食べ、摂取カロリーに応じて体重や見た目が変わるAndroidアプリ「まんぷく相棒」を開発しました。

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)

### 生マッコリの販路開拓インターン

<sub>Misfits Japan（島根県雲南市）· 約1か月</sub>

生マッコリ「OMONA YANGJO」の営業を担当しました。店舗の料理に合わせた提案や、返信しやすい文章への見直しで、DMの返信率を **1%未満から約5%** に改善しました。AIを活用した店舗調査・文章作成・重複確認の手順も整備しました。

| DM送信 | 返信 | サンプル発送 | 契約 |
| :-: | :-: | :-: | :-: |
| **5,001** 店舗 | **225** 店舗 | **59** 件 | **6** 店舗 |

<sub>※ 契約数はインターン後の進展を含みます。</sub>

---

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/yoshiototora)
[![Qiita](https://img.shields.io/badge/Qiita-55C500?style=flat-square&logo=qiita&logoColor=white)](https://qiita.com/yoshiototora)

</div>
