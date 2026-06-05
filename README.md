# Koki Yoshioka

### ユーザーと運用者双方の視点に立ち、技術で課題を根本から解決しきるエンジニア

長崎大学大学院 総合生産科学研究科（M1）で、AIを活用した3D映像合成やコンピュータビジョン（画像認識・映像処理）の研究に取り組んでいます。  
単にプログラムを書くだけでなく、サービスを使う人（ユーザー）の使いやすさと、システムを管理する人（運用者）の作業効率の双方を同時に改善する仕組みづくりを得意としています。

---

## Highlights
- **最優秀賞（警察局長賞）受賞**：警察庁主催サイバー防犯ボランティアコンテストにて、全国約50作品の1位を獲得。
- **App Storeにてグローバル配信**：個人開発した習慣化アプリ「HabitSpark」を公開。ユーザー要望を基にデータベース構造を安全に刷新。
- **科学的データによる実証**：最新AIを活用したVR映像処理により、専門的な評価基準においてVR酔いの改善効果を証明。
- **大学公式システムへの採用**：有志チームを結成し、大学公式のオープンキャンパス案内Webアプリを開発・導入。

---

## Featured Projects

### 1. 長崎大学オープンキャンパス Web アプリ
**高校生の案内パンフレットをスマホで見られる大学公式Webアプリ**
- **課題：** 従来の紙マップはスペースが狭く展示の魅力が伝わらない課題がありました。また、直前まで何度も変更される展示データを修正する運営スタッフの手間が非常に大きいことも問題でした。
- **解決：** 分類タグ（AI、ロボット等）とマップが連動する直感的なUIを設計。専門知識のないスタッフでもExcelデータを貼り付けるだけで一瞬で情報を更新できる簡易管理システムを導入しました。
- **成果：** 担当教授陣へのプレゼンを経て「広報委員会0期生」として公式認定を獲得。当日の様子をまとめた特設Webサイトを公式HPへ掲載。写真担当の1年生と連携した撮影計画や、後輩メンバーを巻き込んだ持続可能な活動体制を構築しました。
- **技術：** React / Next.js / TypeScript / Git / GitHub

### 2. [フィッシング詐欺防止 3DCGアニメーション](https://www.youtube.com/watch?v=2JKH-jF41Kk)
**警察庁主催コンテスト 全国最優秀賞（サイバー警察局長賞）受賞作品**
- **課題：** 従来の防犯啓発は堅苦しく、若年層に関心を持ってもらえない課題がありました。また、映像内の詐欺画面にリアリティがないと実際の被害をイメージしにくい懸念もありました。
- **解決：** 親しみやすい3Dキャラクター（詐欺師＝猫／被害者＝犬）を主人公としつつ、実際のWeb技術で本物そっくりに構築した「偽サイト」を登場させてリアルな演出を徹底。
- **成果：** 3名の有志チームのディレクター兼メインクリエイターとして約50作品中1位を獲得。
- **役割：** ストーリー設計、モデリング、アニメーション編集を主導。他メンバー2名と協働し、背景小物や音響を役割分担して仕上げました。
- **リンク：** [受賞詳細（警察庁）](https://www.npa.go.jp/bureau/cyber/koho/news/2026318contest.html) | [長崎大学 NEWS掲載](https://www.nagasaki-u.ac.jp/ja/news/news4988.html)

### 3. VR酔い低減・適応型動的3D映像合成システム (修士研究)
**最新AIを活用したVR酔い防止と視覚的快適性の科学的実証**
- **課題：** 複数のカメラ映像をつなぎ合わせる際、境界で被写体が崩れたり映像が揺れたりすることが、激しいVR酔い（頭痛や吐き気）を引き起こす原因となっていました。
- **解決：** 撮影環境の動的変化に合わせて、カメラのつなぎ目となる境界線を自動でずらし、映像のズレをリアルタイムに補正するアルゴリズムを設計しました。
- **成果：** 物理的な撮影時のズレを防ぐため、3Dプリンターでカメラ固定用のオリジナル器具を自作。被験者実験を通じてVR酔いの低減効果を客観的・科学的データで証明しました。
- **技術：** Python / PyTorch / OpenCV / Unity / 3Dプリンター（CAD設計）
- **リポジトリ：**
  - [360-video-synthesis-v2](https://github.com/yoshiototora/360-video-synthesis-v2) : 修士研究のメインコード（順次構築予定）
  - [vr-ssq-evaluation](https://github.com/yoshiototora/vr-ssq-evaluation) : 被験者実験（SSQ）における酔いの評価・検証用プログラム
  - [Quest3S_VideoTest](https://github.com/yoshiototora/Quest3S_VideoTest) : Meta Quest 3S デバイスでの検証用（動的表示テストなど）プログラム

### 4. [簡易360°全周囲3D映像のシームレス合成システム](https://github.com/yoshiototora/360-video-synthesis-v1) (卒業研究)
**安価なカメラ3台を用いて低コストで自然な立体VR映像を作り出す映像処理システム**
- **課題：** 数百万円もする特殊なカメラを使わずに安価にVR映像を作ろうとしましたが、映像のつなぎ目で人物の形状が崩れてしまい、不自然に歪んで見える問題がありました。
- **解決：** 深度推定AI「Depth Anything V2」を活用し、人物と背景を自動で切り分けて補正する独自の画像処理プログラムを構築しました。
- **成果：** 不自然さを極限まで排除したVR空間の再現に成功し、現在の修士研究の土台となっています。
- **リポジトリ：**
  - [360-video-synthesis-v1](https://github.com/yoshiototora/360-video-synthesis-v1) : 卒業研究のメインコード

### 5. [HabitSpark（iOSアプリ）](https://apps.apple.com/jp/app/habitspark/id6762178668)
**「失敗から学ぶ」ことで挫折を防ぐ習慣化支援アプリ**
- **課題：** 既存の多くの習慣化アプリは「毎日完璧に続けること」を前提としており、一度サボると挫折しやすい点、また目標が大きすぎて行動に移しにくい課題がありました。
- **解決：** 
  1. 目標を「月・週・日次」に段階的に分解できる設計。
  2. 失敗した日はKPT法で振り返りを行い、Try（改善策）がそのまま翌日のタスクになる独自のサイクル。
- **成果：** App Storeレビューの要望（出来なかったTryの翌日引き継ぎ）を元に、自動引き継ぎ機能を実装。さらに、3日未完了が続いたTryを「Problem（課題）」へ自動差し戻しして目標設定の難易度を見直すUXを構築。既存ユーザーのデータを一件も壊すことなく、SwiftDataによるデータ構造の刷新（安全なマイグレーション）をやり切りました。
- **技術：** Swift / SwiftUI / SwiftData / Git
- **リポジトリ：** [GoalTracker (HabitSparkソースコード)](https://github.com/yoshiototora/GoalTracker)

---

## Skills & Tools

### Languages & Frameworks
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=Swift&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-00599C?style=flat-square&logo=Swift&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=PyTorch&logoColor=white)

### Tools & Creative
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=OpenCV&logoColor=white)
![Blender](https://img.shields.io/badge/Blender-F5792A?style=flat-square&logo=Blender&logoColor=white)
![Adobe Premiere Pro](https://img.shields.io/badge/Premiere_Pro-9999FF?style=flat-square&logo=Adobe%20Premiere%20Pro&logoColor=white)
![3D Printing](https://img.shields.io/badge/3D_Printing-000000?style=flat-square&logo=Ultimaker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

---

## Core Strengths
1. **ユーザーと運用者双方の視点：** 利用者の使いやすさと管理側の運用効率化を両立するプロダクト設計力。
2. **課題の構造化と完遂力：** 不確実な課題（データベースの安全な移行や、VR酔い低減など）を構造的に分解し、ハード・ソフト問わず実装しきる力。
3. **対話に基づくプロダクト改善：** App Storeレビューやユーザーへの対話を基に、課題を的確に抽出して機能追加や体験（UX）向上に繋げる姿勢。

---

## Profile / Contact
- **University:** 長崎大学大学院 総合生産科学研究科 コミュニケーションメディア研究室 (M1)
- **Experience:** LITALICOワンダー プログラミング講師（小中学生向けにMinecraft/Blenderの指導）
- **Technical Writing:** [Qiita (@yoshiototora)](https://qiita.com/yoshiototora)

---

「ユーザーと運用者双方の課題を技術で根本解決し、持続可能な価値を生み出す」ことでビジネスに貢献します。
