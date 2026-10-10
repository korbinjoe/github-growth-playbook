# GitHub成長調査：中国本土の作者と個人開発者の拡散経路

[English](../../../research/github-personal-developer-growth-2024-2026.md) | [简体中文](../../zh-CN/research/github-personal-developer-growth-2024-2026.md) | **日本語** | [Français](../../fr/research/github-personal-developer-growth-2024-2026.md) | [Deutsch](../../de/research/github-personal-developer-growth-2024-2026.md)

整理日：2026-10-10  
対象期間：2024-10-10〜2026-10-10  
焦点：最初の利用者、拡散の転機、応用できる告知行動。

## 主な発見

参考になる経路は、**関連コミュニティで評価を得た後、見える成果、作者の振り返り、拡張できる仕組みによって第三者の紹介につなげること**です。

| 事例 | 拡散の動機 | 他者が説明できる内容 |
| --- | --- | --- |
| BettaFish | 成果と作者の経験 | 成果に裏付けられた学生の経験とAI開発の学び |
| PDFMathTranslate | 論文読解の具体的問題と配置の比較 | 便利さを見せやすいツール |
| BongoCat | 視覚的体験と利用者の制作 | 理解しやすい製品と継続的なモデル・外観 |
| Claude Code Router | 人気製品の補完需要 | 利用者が知っている製品の解決策 |

AI製品ではPDFMathTranslateのデモとBettaFishの振り返りを組み合わせ、価値を確認してから解決過程を説明する方法を推奨します。

## 範囲と証拠

- 対象は拡散の時期であり、リポジトリの作成日ではありません。既存製品も含みます。
- Starは当時の概算累計で、2年間の増分や利用者数ではありません。キャッシュに差があり得ます。
- 中国語文書だけでは本土の作者と確認できません。所在地、大学、公式チーム資料を別に記録します。
- 個人の起点、共同開発、企業育成を分けます。
- 全言語とプログラミング言語別のTrendingを区別します。順位は流入経路を示しません。
- 事実、自己申告、推論を分けます。独立したチャネル監査はなく、順序だけで原因を断定できません。

## プロジェクト一覧

### 本土の作者・チームの根拠があるもの

| プロジェクト | 根拠 | 概算累計Star | 対象期間の記録 |
| --- | --- | ---: | --- |
| [BettaFish](https://github.com/666ghj/BettaFish) | [BaiFu／郭航江：上海と本土の大学](https://github.com/666ghj) | 42.4k | 作者によればコミュニティで約1,000、振り返り拡散後の1週間で約20,000追加 |
| [Claude Code Router](https://github.com/musistudio/claude-code-router) | [musistudio：杭州](https://github.com/musistudio) | 37.6k | 2025年2月投稿、5月末再設計、6〜7月集中、6月26日全言語3位 |
| [BongoCat](https://github.com/ayangweb/BongoCat) | [ayangweb：青海](https://github.com/ayangweb) | 23.9k | 2025年4月V2EX、5月ニュースレター、6月独自モデル。TypeScript Trendingに複数回 |
| [PDFMathTranslate / pdf2zh](https://github.com/PDFMathTranslate/PDFMathTranslate) | [Byaidu：中国電子科技大学](https://github.com/Byaidu)、後に共同開発 | 37.3k | 2024年11月投稿・記事、2025年論文で222,000超のダウンロードを報告 |
| [Cherry Studio](https://github.com/CherryHQ/cherry-studio) | [CherryHQ：上海のチーム](https://github.com/CherryHQ) | 52.5k | 対象期間以前の製品。創業者インタビュー紹介はDeepSeek流行時の利用者増を記録 |
| [XiaoZhi AI](https://github.com/78/xiaozhi-esp32) | 黄冠／虾哥、深圳Tenclass。[公式紹介](https://www.tenclass.com/news/news240/) | 30.6k | 2025年1月11日全言語1位。企業・チーム支援があるハードウェア事例 |
| [MinerU](https://github.com/opendatalab/MinerU) | [上海AI研究所OpenDataLab](https://opendatalab.github.io/index.html) | 81.3k | 既存製品、2024年11月全言語上位3位に複数回。下流への連携 |
| [LLaMA-Factory](https://github.com/hiyouga/LlamaFactory) | [鄭耀威：北京](https://github.com/hiyouga) | 75.4k | 個人起点で長期成長。2026年2月Python Trending。期間内の新規製品ではない |
| [DeepSeek-R1](https://github.com/deepseek-ai/DeepSeek-R1) | DeepSeekチーム | 91.9k | 2025年1月公開。重み、技術報告、評価、蒸留モデル。研究規模より公開方法が参考になる |

順位と公開の根拠：[CCR](https://www.star-history.com/musistudio/claude-code-router/)、[BongoCat](https://www.star-history.com/ayangweb/bongocat/)、[XiaoZhi](https://www.star-history.com/78/xiaozhi-esp32/)、[MinerU](https://www.star-history.com/opendatalab/mineru/)、[LLaMA-Factory](https://www.star-history.com/hiyouga/llamafactory/)、[DeepSeek](https://api-docs.deepseek.com/zh-cn/updates/)。

### 作者所在地の根拠が不十分な人気製品

製品や拡散の参考ですが、厳密な本土作者の一覧には未収録です。累計人気だけでは対象期間の急増を証明できません。

| プロジェクト | 概算累計Star | 確認した機能 | 想定する仕組み：推論 |
| --- | ---: | --- | --- |
| [CC Switch](https://github.com/farion1231/cc-switch) | 141.9k | AI開発ツールの提供者設定・切替のGUI | 人気エコシステムの頻繁な補完需要 |
| [MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) | 129.3k | 題材から文章、音声、素材、字幕、動画へ | 完成結果をデモや手順で説明しやすい |
| [Prompt Optimizer](https://github.com/linshenkx/prompt-optimizer) | 37.2k | プロンプト改善、試験、比較。[作者サイト](https://always200.com/) | 抽象的能力を比較可能にする |
| [TradingAgents-CN](https://github.com/hsliuping/TradingAgents-CN) | 32.2k | 元製品を中国市場・データ・モデル向けに適応 | 実業務のローカライズ。元製品を明示する |

MoneyPrinterTurboは2025年5月と9〜10月に全言語1位の記録があります。[履歴](https://www.star-history.com/harry0703/moneyprinterturbo/)

### MiroFish：その後の企業育成

BettaFishと同じ作者の[MiroFish](https://github.com/666ghj/MiroFish)は[プロフィールの記録](https://github.com/666ghj)で約77.5k Starでした。[振り返り](https://linux.do/t/topic/1697717)には開発時のShanda支援とその後の出資・育成が明記されています。個人の起点はBettaFish、評判と資源の次製品への接続はMiroFishで検討します。

## 四つの個人開発経路

### BettaFish

2026年3月の振り返りでは、200超の既存Star、反応の少ない投稿、コミュニティ活動、約1か月で1,000、その後Xiaohongshuの振り返りとwhy技术などの紹介が記録されています。急増期1週間で約20,000追加は作者の申告です。[原投稿](https://linux.do/t/topic/1697717)

推論：最初の成果が個人の物語を支え、技術読者と一般読者の両方に説明しやすくなります。需要、判断、失敗、反応を残し、実際の振り返りとデモを用意します。幸運な拡散は保証できません。[詳細](../cases/bettafish.md)

### PDFMathTranslate

2024年11月6日の作者投稿から19日の編集記事へ。後にWindows、GUI、Zoteroの入口。2025年7月に222,000超のダウンロードを申告しましたが、固有利用者数ではありません。[投稿](https://meta.appinn.net/t/topic/62859/1)、[記事](https://www.appinn.com/pdf-math-translate/)、[文書](https://github.com/PDFMathTranslate/PDFMathTranslate/blob/main/docs/README_zh-CN.md)、[論文](https://arxiv.org/abs/2507.03009)

推論：数式、図、配置を保つ結果は説明しやすくなります。初期記事はまだコマンドラインと注意。比較、試用、対象、制限、連絡先を提供し、導入を改善します。表、引用、使える出力など具体的な価値を示します。[詳細](../cases/pdfmathtranslate.md)

### BongoCat

2025年4月22日紹介、5月9日ニュースレター、6月4日モデル取り込みと制作手順・動画・作品集。Bongo Cat Mverに着想を得ています。[紹介](https://www.v2ex.com/t/1127289)、[掲載](https://www.ruanyifeng.com/blog/2025/05/weekly-issue-347.html)、[更新](https://v2ex.com/t/1136196)

推論：コミュニティと編集者が発見を助け、後の制作機能が新しい素材を生みます。モデルは後の段階で、初期の原因とは未確認です。例、手順、素材、完成品を用意し、見せたい成果を作れるようにします。[詳細](../cases/bongocat.md)

### Claude Code Router

2025年2月25日の検討は `claude-code-reverse` にリンク。5月末再設計、6〜7月Trending、6月26日全言語3位。[投稿](https://www.v2ex.com/t/1114144)、[振り返り](https://github.com/musistudio/claude-code-router/blob/main/blog/zh/项目初衷及原理.md)、[履歴](https://www.star-history.com/musistudio/claude-code-router/)

推論：既知の元製品がモデル選択、設定、費用改善の需要を生みます。数か月の改善とコメント対応も重要です。なじみの操作の具体的改善を見せ、利用者の表現に合わせて反応を製品に反映します。[対話](https://global.v2ex.com/t/1114144)、[詳細](../cases/claude-code-router.md)

## 補足の学び

- **Cherry Studio：** インタビュー紹介と時刻案内はDeepSeekによる流入を説明。音声全体の逐語確認はしていません。共創・報酬制度の初回集計は2025年第3四半期。推論：流行時は初回利用を整え、後に明確な貢献機会と評価を用意します。[番組](https://podcasts.apple.com/ma/podcast/cherry-studio-%E7%8E%8B%E6%96%B0%E9%93%AD-2-%E4%B8%AA%E4%BA%BA-github-42k-%E6%98%9F-%E4%BB%A3%E7%A0%81%E8%B4%A1%E7%8C%AE%E7%AC%AC%E4%B8%80%E5%90%8D%E6%98%AF-claude/id1671502201?i=1000756144697&l=ar)、[制度](https://github.com/CherryHQ/cherry-studio#-developer-co-creation-program)
- **XiaoZhi AI：** ファームウェア、デモ、手順、基板対応。2025年6月にはSeeed Studioとの共同イベント。推論：メーカー、制作者、解説者がそれぞれ成果を示せます。企業支援の事例です。[イベント](https://www.tenclass.com/new_pages/det_news_273.html)
- **MinerU：** RAGFlowの2025年10月23日版がPDF解析に採用。下流での採用は確認できますが流入量は不明。推論：API、プラグイン、例、互換性文書が連携者を継続的紹介者にします。[リリース](https://github.com/infiniflow/ragflow/blob/main/docs/release_notes.md)

## 実行手順

1. 実際のデモ、短い入口、例、制限を用意する。
2. 二つの関連コミュニティで試用、用途、質問、共有、手順、貢献を記録する。
3. 需要、反応、判断、失敗、結果、学びを証拠付きで振り返る。
4. 編集者や連携者へ素材を渡し、注目後も導入と初回利用を維持する。

これは提案であり、全作者が全項目を実施したという記録ではありません。[ガイドと文案](../playbooks/launch-and-distribution.md)、[事例テンプレート](../templates/case-study.md)、[実験テンプレート](../templates/growth-experiment.md)を参照してください。

## 未解決の帰属

BettaFish数値は主に自己申告。PDFMathTranslateの掲載、BongoCatの時系列、CCRの改善は確認済みですが、経路別寄与は定量化できません。四製品の所在地は要確認。2年間の全Star増分も再構成していません。

次の調査では作者への取材や許可された流入データから、最初の経路、最大の紹介、試用成功、継続利用を調べます。修正日と指標の定義を残します。

## 結び

確認できる成果、明確な紹介、本物の振り返り、再利用できる素材を優先します。コミュニティは改善、第三者は発見、拡張と維持は実利用を助けます。これらは判断の材料であり、成長、資金調達、売上の保証ではありません。
