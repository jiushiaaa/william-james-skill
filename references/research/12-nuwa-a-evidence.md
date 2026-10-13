# 威廉·詹姆斯：原版女娲独立研究补证

研究补证；不评分，不授予A级，不等于全集完成

2026-10-13。默认中性思想；独立可选表达只在用户明确选择时启用，文游禁文风。未改canonical；未读答题与评分结果。

## 覆盖与未读
- **The Will to Believe（1896/1897）**：继承I140–151、VII–X221–280；未读：全论文集、Clifford原文、通信。
- **Pragmatism（1907）**：继承II344–364；本轮VI743–771及839–868两段连续阅读；VI20段长度限定样本逐段查看；未读：其余讲次及VI未列间隔并非连续已读。
- **The Varieties of Religious Experience / Essays in Radical Empiricism（1901–1902 / 1912结集）**：继承宗教经验I68–99；激进经验主义II327–340、IV704–716、V737–744、X1202–1205；未读：完整心理学原理、后期多元论及所列作品全书。

标为继承的范围来自已读本地来源目录及10/11记录，不宣称本轮重新阅读所有原作；网页行号为工具当时定位，复核须结合章节/段落指纹。

## 本轮连续原作补证
- [VI网页743–771及839–868；两块各自连续，二者间未连续补齐](https://www.gutenberg.org/files/5116/5116-h/5116-h.htm)：真观念的运作涉及验证与经验引导；直接验证并非唯一形式，无关当前行动的真理仍可储存；作者反对随心所欲即真。 边界：补强边界及表达，不能把真理理论当错信/漏信风险计算的第二次跨域运行。

## 逐项三验证审查（不打分）

### 真正选项资格
- 宗教：[定位](https://www.gutenberg.org/cache/epub/26659/pg26659-images.html) I及VII–X既读；活的、被迫的、重大的选项。
- 社会合作/信任：[定位](https://www.gutenberg.org/cache/epub/26659/pg26659-images.html) IX既读；某些事实需先行信任才可能出现。
跨域：原作有两个领域，同篇论证中的局部见证；不等于宗教事实已被合作成功证明。
生成力：可生成何时需等待证据的边界，未独立测试。 独立测试未完成。
区分度：资格条件限制意志许可，区别于有信念就能成功。
地位：保留有限程序；未完成三重独立验证。

### 错信/漏信风险
- 宗教判断：[定位](https://www.gutenberg.org/cache/epub/26659/pg26659-images.html) VII–X既读；避免错误与取得真理不是同一命令。
- 合作机会：[定位](https://www.gutenberg.org/cache/epub/26659/pg26659-images.html) IX既读；拒绝先信可能关闭机会。
跨域：两域共享同篇原理，可有限见证；本条与真正选项的独立性仍须检验，不用新VI凑第二模型证据。
生成力：可显露两种风险，不提供概率数值公式；未独立测试。 独立测试未完成。
区分度：将漏失可能真理也作为认知风险，并非一般成本收益分析。
地位：保留有限程序；未完成三重独立验证。

### 发生/意义/价值分问
- 宗教体验：[定位](https://www.gutenberg.org/cache/epub/621/pg621-images.html) I68–99既读；生理发生条件与价值判断不等同。
- 一般真理/日常行动：[定位](https://www.gutenberg.org/files/5116/5116-h/5116-h.htm) VI743–771；观念如何导向经验与当前对象是否有用分问。
跨域：第二域与原模型有关但不是同一发生—价值区分的完整复现，仍单域较强、跨域不足。
生成力：能避免由起因直接否定价值或由好效果证明神迹；未独立测试。 独立测试未完成。
区分度：具体经验路径和生活后果受外部控制，不能只说尊重感受。
地位：保留有限程序；未完成三重独立验证。

## 可复核表达抽样
见可复跑脚本nuwa_a_research_2_sampler.py：固定种子20261013，HTML p序号从0起，规范化空白后取SHA256。通常仅30–180词段，故不是全文均匀抽样；所有最终选中段已在工具输出逐段实际查看。霍克海默为10个合格段的全取；奥斯汀未建立可靠分段。
实取20段；指标：`{"words": 1744, "sentences": 87, "question_sentences": 2, "first_person_tokens": 4, "contrast_tokens": 14, "mean_words_per_sentence": 20.046, "question_sentence_ratio": 0.02299, "first_person_per_1000_words": 2.294, "contrast_per_1000_words": 8.028}`。类比密度与确定性比例未计算。
逐段来源/HTML定位/指纹/原始计数见[william-james-perspective-sample.json](william-james-perspective-sample.json)。

可直接用于独立表达附录的高层规则：
- 从日常例子引入争点，向读者连问两三个具体差别，再压成概念区分。
- 采用过程性类比后立即交代哪些经验能支持或阻止它。
- 可以有讲演式的直接称呼和轻微讽刺；同时把对方论点讲清。

反模式与边界：
- 不把“有用”反复当口号，不模仿原文全大写或现金隐喻。
- 不将作者虚构反对者的段落当作者本人立场。
- 不以情绪强度、好后果替代外部事实核查。
- Length-restricted sampling (30–180 words), not representative of the full work; Horkheimer uses ten eligible original paragraphs without length filtering.
- Sentence boundary regex splits after punctuation; abbreviations/quoted questions may distort counts.
- First-person and contrast are lexical counts, not manually coded rhetorical intentions.
- Analogy density and certainty ratio not measured.
- Electronic transcription not collated with first-edition page images.
- 中文输出只迁移高层修辞功能，不把英法词长/词频硬套到中文。
- 统计中的第一人称可来自作者构造的示范/虚拟对话，不证明真实自述；所概述的他人观点也不是作者赞同。
- 只用于用户明确选用的独立表达附录；默认中性思想，文游禁文风。

## 两项有原作依据的张力
- 尽力避免错误；同时亦不愿因无限等待错失可得到的真理。[原作定位](https://www.gutenberg.org/cache/epub/26659/pg26659-images.html)：VII–X既读。共同要求之间的张力，非简单自相矛盾。
- 真理在经验引导和确认过程中实现；同时经验与已有真理又限制愿望，不能任意把愉快说法当真。[原作定位](https://www.gutenberg.org/files/5116/5116-h/5116-h.htm)：VI753–771与856–868。共同要求之间的张力，非简单自相矛盾。

## 尚待完成
- 第三程序缺明确第二域复现；前两条独立性需盲测。
- 心理学原理、通信及完整后期著作未补足。
- 表达样本只取VI讲30–180词段，不能作为心理学长篇或私人书信的指纹。

访问：
- web.open成功；requests只读获取用于段落计数；仅保留SHA256、指标和原创笔记，不保存原作全文。

三道已知立场题均为作者实际讨论的问题；仅设计，不作答、不评分。逐题方向及来源另见proposals同名JSON。
