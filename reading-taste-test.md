# Reading Taste Test Framework

A comprehensive, multi-round reading preference interview framework designed to infer a reader's taste profile from their genre preferences, reading history, difficulty tolerance, and reactions to books, then generate tailored recommendations.

## Core Principle

Treat reading taste as *multi-dimensional*. Do not collapse it into a single label too early.

A good analysis should track:
- **Content type**: fiction / nonfiction / mixed
- **Preferred domains**: literature, history, social science, philosophy, science, business, psychology, etc.
- **Cognitive style**: narrative-driven, framework-driven, knowledge-dense, argument-driven, tool-driven, curiosity-driven
- **Difficulty tolerance**: light, moderate, hard, very hard
- **Reading purpose**: entertainment, insight, self-cultivation, practical use, identity exploration, research
- **Format preference**: long-form, short-form, essays, dense theory, popular science, reference, oral-history, case studies
- **Author/source preference**: domestic, translated, classic, contemporary, no preference
- **Evaluation style**: rating-led, reputation-led, content-led, independent, trust-your-own-taste

## Test Design Philosophy

This framework supports *longer and richer* tests for maximum precision.

### Allowed Question Styles
- Multiple choice with more than 4 options
- Multi-select questions
- Ranking questions
- A/B/C/D/E style questions
- Follow-up branching questions
- Open-ended questions about books read, loved, or disliked
- "Choose all that apply" questions

### What Makes the Test More Accurate
Accuracy improves when you ask about:
1. *What the user has actually read*
2. *What they liked or finished*
3. *What they abandoned or bounced off*
4. *What they want from reading right now*
5. *What kind of book structure they tolerate*
6. *Whether they prefer depth, breadth, novelty, or comfort*

## Recommended Multi-Round Structure

Use 3 rounds when the user wants a precise profile.

### Round 1: Fast Orientation
**Goal**: identify the main reading family and cognitive style.

**Suggested question themes**:
- preferred categories
- desired reading outcome
- preferred density and difficulty
- preference for domestic vs translated
- preference for fiction vs nonfiction
- response to ratings and popularity

Keep this round concise but broader than a normal quiz.

### Round 2: Book-History Calibration
**Goal**: infer taste from real examples.

Ask the user to name:
- 3 books they loved
- 3 books they liked or respected
- 3 books they disliked, DNF'd, or found boring

For each book, ask at least one of the following:
- what they liked about it
- what they disliked about it
- whether they finished it
- whether they would recommend it
- whether they want similar or opposite books

Use these responses to detect:
- recurring themes
- pacing tolerance
- appetite for theory
- openness to translation/classics
- favorite tone and structure

### Round 3: Fine-Grained Preference Map
**Goal**: distinguish close-but-different tastes.

**Useful dimensions**:
- narrative vs essay vs argument vs case study
- big ideas vs specific details
- global history vs local history
- social theory vs psychology vs economics
- scientific explanation vs humanistic interpretation
- practical use vs aesthetic pleasure
- classic canon vs contemporary discovery
- mainstream high-rated vs niche high-quality
- optimistic vs skeptical tone
- text-heavy vs example-heavy books

## Extended Question Design

When the user explicitly wants a more accurate test, do not keep the questionnaire short. It is valid to ask many questions across multiple rounds, especially if the goal is to understand real taste rather than make a quick guess.

### Design Rules for Richer Tests
- It is fine to have more than 4 options per question.
- It is fine to use multi-select questions with 6–10+ options.
- It is fine to ask the user to score books on a 1–10 scale.
- It is fine to ask about books they have not read yet, as long as you separate aspiration from revealed taste.
- It is fine to ask follow-up questions after every answer if that answer changes the hypothesis.
- Prioritize precision over brevity when the user asks for a deeper profile.

### Book-Familiarity Ladder
A strong deep test should try to learn all of these, in order:
1. books the user knows by reputation only
2. books the user has heard of but not read
3. books the user has started and abandoned
4. books the user finished but disliked
5. books the user liked
6. books the user loved
7. books the user rereads, recommends, or treats as reference points

This ladder is often more useful than genre labels alone.

## Suggested Question Bank

You do not need to ask all of these at once. Pick what is relevant, then branch.

### 1) Reading Goals
- What do you mainly want from books?
- Which goal matters most right now?
  - relaxation
  - intellectual stimulation
  - knowledge expansion
  - worldview expansion
  - practical improvement
  - emotional resonance
  - aesthetic pleasure
  - professional utility

### 2) Content Domains
- Which domains do you read most often?
  - literature
  - history
  - philosophy
  - sociology
  - economics
  - psychology
  - science
  - technology
  - business
  - biography/ memoir
  - politics
  - religion / myth / classics

### 3) Format and Structure
- Which format feels best?
  - story-driven novel
  - essay collection
  - long-form non-fiction
  - short, dense theory
  - textbook-like exposition
  - case-driven explanation
  - interview/oral history
  - concept-by-concept reference

### 4) Difficulty and Pacing
- How hard do you like books to be?
  - easy and smooth
  - moderately challenging
  - substantial and dense
  - very hard / rewarding only if worth it

- Which pacing do you prefer?
  - fast and addictive
  - steady and reflective
  - slow but deep
  - variable depending on topic

### 5) Author/Source Preference
- Do you prefer:
  - Chinese authors
  - translated books
  - classics
  - contemporary books
  - no strong preference

### 6) Evaluation Style
- How do you choose books?
  - follow high ratings
  - follow trusted curators
  - follow topics I care about
  - follow authors I already know
  - follow my own curiosity
  - combine all of the above

### 7) Tolerance and Aversion
- What kind of books do you usually dislike?
  - too shallow
  - too academic
  - too long-winded
  - too emotional
  - too practical
  - too abstract
  - too repetitive
  - too ideological
  - too plot-heavy with little insight
  - too little plot and too much theory

### 8) Book-History Examples
- Name a few books you loved.
- Name a few you admired but did not necessarily love.
- Name a few you tried and dropped.
- What pattern do those books share?

### 9) Comparative Taste Checks
Use paired choices when the user wants precision:
- A) big-picture explanation vs B) close reading/detail
- A) deep theory vs B) accessible overview
- A) new ideas vs B) reliable classics
- A) human stories vs B) system analysis
- A) local context vs B) global view
- A) single-topic focus vs B) broad survey

## Interview Flow

A strong workflow is:
1. Start with 6–10 broad questions.
2. Based on the answers, ask 3–5 follow-ups.
3. Ask for concrete books read, liked, or disliked.
4. Use the examples to refine the profile.
5. Offer a tailored recommendation list and explain why it fits.

## How to Handle Multi-Select Answers

If the user gives multiple letters or multiple books, treat that as a signal of mixed taste.
Do not force a single label.
Instead, identify:
- dominant preference
- secondary preference
- weak or occasional preference

## How to Analyze Book-History Answers

When the user mentions books, inspect for:
- genre overlap
- shared themes
- shared scale of ideas
- similar narrative pace
- recurring author origin
- recurring tone
- whether the user finished the book
- whether the user rereads or recommends it

**Useful signals**:
- Loved *deep books* → strong appetite for intellectual density
- Loved *easy but smart books* → medium depth, high readability
- Loved *classic literature* → patience for style and ambiguity
- Loved *science/popular science* → explanation and systems thinking
- Loved *history* → temporal and structural curiosity
- Loved *psychology/self-knowledge* → introspective and applied cognition
- DNF'd *too academic* → needs clearer prose or concrete examples
- DNF'd *too plotty* → wants more substance
- DNF'd *too much jargon* → values clarity over status

## Output Requirements

A useful result should include:
1. A one-paragraph reading profile
2. A bullet list of the key taste dimensions
3. A note on likely dislikes or friction points
4. A recommendation list grouped by fit strength
5. A short "next questions I'd ask if we wanted even more precision" section when appropriate

## Recommendation Strategy

When recommending books:
- Match the reader's dominant dimensions first
- Use a mix of core-fit and stretch-fit suggestions
- Explain briefly why each title fits
- Include a few "bridge books" if the reader is exploratory
- If the user gave example books, prioritize books that rhyme with those examples in structure, ambition, and tone

### Recommendation Tiers
Use labels like:
- *Core fit* — very likely to enjoy
- *Strong fit* — likely to enjoy
- *Bridge fit* — may enjoy if curious
- *Stretch fit* — useful but not guaranteed

## Profile Archetypes

You can label readers with more nuanced archetypes, such as:
- Knowledge-density reader
- Framework builder
- Narrative explorer
- Practical upgrader
- Classic-and-ideas reader
- Methodical sampler
- High-certainty curator
- Mixed-domain generalist
- Deep-dive specialist
- Curiosity-led explorer

## Example Response Structure

1. "我大概能把你的阅读口味分成几条线：……"
2. "你更像是……"
3. "从你读过/喜欢/不喜欢的书看，……"
4. "你可能会特别喜欢……，也可能会避开……"
5. "如果想更准，我下一轮会问你…… "

## Pitfalls

- Do not overfit from only one or two books
- Do not treat high ratings as the only signal
- Do not assume literary taste equals nonfiction taste
- Do not confuse "读得多" with "偏好明确"
- Do not force a single label if the user clearly has multiple reading modes
- Do not ask too few questions when the user explicitly wants precision

## Best Practice

If the user wants a reusable test for other people, make the questionnaire easy to copy and answer in chat.
If they want maximum precision, favor the multi-round mode with book-history calibration.

Do not store temporary test results in long-term memory unless the user explicitly asks you to remember them.

## Recommended Operating Modes

### 1) Quick Mode (Lightweight)
**Use when**: user says things like "随便测一下", "简单看看我的口味", "先来个简版"

**Structure**:
- 4–6 orientation questions
- 1 short book-history prompt (favorite / disliked / DNF)
- 1 concise profile
- 5–8 recommendations

### 2) Standard Mode (Default)
**Use when**: user wants decent precision but not a very long interview.

**Structure**:
- Round 1: 6–8 orientation questions
- Round 2: 3 loved / 3 disliked-or-DNF books
- Round 3: 3–5 fine-grained comparison questions
- Final profile + tiered recommendations

### 3) Deep Mode (High Precision)
**Use when**: user explicitly wants a thorough reading profile.

**Structure**:
- Round 1: orientation
- Round 2: detailed reading history
- Round 3: structural and tonal preferences
- Round 4: recommendation calibration (reacting to candidate books)
- Final profile with confidence notes and uncertainty notes

## Conversation Templates

### Opening Template

You can begin with something like:

"我可以用一个多轮的小测试来判断你的阅读口味，不只是按类型分，还会看你偏好的密度、结构、目标和你真实喜欢/弃读过的书。你想要：
1. 简版（3–5分钟）
2. 标准版（更准）
3. 深度版（最准确）"

### Round 1 Template

Use a compact block such as:

"先做第一轮定位，你可以直接按题号回答：
1. 你最近更想读：小说 / 历史 / 社科 / 哲学 / 科普 / 传记 / 其他
2. 你读书主要为了：消遣 / 获取知识 / 建立框架 / 开阔视野 / 工作实用 / 情感共鸣
3. 你能接受的难度：轻松 / 中等 / 偏难 / 很难但值得
4. 你更喜欢：叙事推进 / 观点分析 / 案例解释 / 体系化梳理
5. 你更常避开什么：空泛 / 说教 / 术语堆砌 / 太浅 / 太学术 / 太啰嗦"

### Round 2 Template

"第二轮用你真实读过的书来校准，请尽量具体：
1. 说 3 本你很喜欢的书
2. 说 3 本你觉得还行但没那么喜欢的书
3. 说 3 本你不喜欢、弃读或觉得无聊的书
4. 每类里任选 1–2 本，简单说一句为什么"

### Round 3 Template

"最后做几道精细区分题：
1. 你更偏向：大框架解释 / 具体细节与文本
2. 你更偏向：新观点 / 经典定评
3. 你更偏向：人的故事 / 制度与结构
4. 你更偏向：通识综述 / 单点深挖
5. 你更偏向：清晰直白 / 风格浓、可反复咀嚼"

## Output Format

When delivering the final result, prefer this structure:

### 1. 一段式阅读画像
In 4–8 sentences, summarize the user's reading style, preferred domains, and likely motivations.

### 2. 关键维度拆解
Use bullets such as:
- 内容倾向：
- 认知风格：
- 难度容忍度：
- 结构偏好：
- 阅读目标：
- 选书方式：

### 3. 可能的雷区 / 摩擦点
List what the user is likely to dislike, bounce off, or only tolerate in small doses.

### 4. 推荐清单（分层）
Group recommendations as:
- Core fit
- Strong fit
- Bridge fit
- Stretch fit

For each book, include:
- title + author
- 1 short reason it fits
- optional note: "如果你最看重的是 X，就优先这本"

### 5. 如果继续测，下一轮该问什么
List 3–5 next questions that would sharpen the profile further.

## Analysis Heuristics

When converting answers into a profile, look for these patterns:

### High-Density / Framework Reader
**Signals**:
- likes system-building books, big-picture explanations, intellectual compression
- dislikes fluff, repetition, shallow bestsellers
- often likes history of ideas, philosophy, social science, hard popular science

**Recommendation style**:
- prioritize dense but clear books
- explain the conceptual payoff
- avoid overly trend-driven recommendations

### Narrative + Insight Reader
**Signals**:
- wants stories, but not empty stories
- likes novels, memoir, reportage, or narrative nonfiction with ideas embedded inside
- dislikes purely abstract theory and textbook exposition

**Recommendation style**:
- recommend books where insight is carried by narrative energy
- prioritize tone, voice, and emotional-cognitive payoff

### Practical / Model-Building Reader
**Signals**:
- likes psychology, decision-making, economics, tools, frameworks
- asks whether a book is useful, applicable, or worldview-shifting
- tolerates some repetition if the framework is strong

**Recommendation style**:
- separate genuinely useful books from inflated airport-business books
- identify whether the user wants actionable tactics or durable mental models

### Classic-and-Ideas Reader
**Signals**:
- accepts slower pacing for style, ambiguity, and long-term value
- likes classics, canons, essays, philosophy, and literary depth
- may dislike purely efficiency-oriented recommendations

**Recommendation style**:
- include both accessible entry points and heavier canonical works
- explain why a classic is worth the cost

## Calibration Rules

- If the user names books across very different domains, do not flatten them into one taste line; identify primary and secondary modes.
- If the user says "我什么都看", force yourself to ask for concrete examples before trusting the claim.
- If the user gives only aspirational books (books they want to like), explicitly separate aspirational taste from revealed taste.
- Distinguish between "respect" and "enjoyment". A user may admire a book without wanting more books like it.
- Distinguish between "too difficult" and "too boring". Both lead to DNF, but imply different recommendation strategies.

## Reusable Questionnaire Format

If the user wants a test they can forward to a friend, provide a clean copyable template like this:

"阅读口味测试（标准版）
第一部分：基础偏好
1. 你最常读哪些类型？
2. 你读书最主要是为了什么？
3. 你能接受多高的阅读难度？
4. 你更喜欢叙事、观点、案例还是框架？
5. 你最常放弃哪类书？

第二部分：真实阅读记录
6. 说 3 本你很喜欢的书。
7. 说 3 本你觉得一般的书。
8. 说 3 本你不喜欢/弃读的书。
9. 分别简单说下原因。

第三部分：精细偏好
10. 更喜欢大框架还是细节？
11. 更喜欢经典还是新书？
12. 更喜欢人的故事还是制度/结构？
13. 更喜欢综述还是深挖？
14. 更喜欢清晰直白还是风格浓烈？"

## What Good Recommendations Should Feel Like

A strong result should make the user feel:
- "你真的看懂了我读书时在追求什么"
- "你不是只按类型给我贴标签"
- "这些书和我喜欢/不喜欢的例子之间是有逻辑关系的"

If the recommendations do not clearly connect back to the user's stated examples and aversions, the analysis is not finished.
