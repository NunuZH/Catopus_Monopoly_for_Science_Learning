# Catopus_Monopoly_for_Dialogic_Science_Learning

「学术游园会」是一款专为课堂教学、学术沙龙设计的网页互动游戏。它将“大富翁”的经典玩法与“学术对话”深度结合，旨在通过角色扮演、线索收集和逻辑对话，让参与者在轻松的氛围中完成知识的内化与应用。

This project is an interactive web-based game designed specifically for collective learning. It integrates the classic gameplay of "Monopoly" with the dynamics of "academic dialogue," aiming to facilitate the internalization and application of knowledge among participants—within a relaxed atmosphere—through role-playing, clue gathering, and reasoned dialogue.

---

## ✨ 核心特色
* **🧠 知识论证系统：** 该游戏需要玩家通过「现象」、「理论」、「实验」三位一体的卡牌组合进行逻辑推理、验证。
* **The Argumentation System:** The game requires players to engage in logical reasoning and argumentation by utilizing a tripartite combination of cards: "Phenomena," "Theories," and "Experiments".
* **⚔️ 多元对话策略：** 提供「知识链接」、「极限挑刺」、「灵魂拷问」、「现象拆解」四种踢馆模式，深度锻炼批判性思维。
* **The Dialogic Moves:** Features four distinct modes ("Coordination", "Challenge", "Inquiry", "Refer to Wider Context") designed to rigorously invite critical thinking and dialogic interactions.
* **⚒️ 老师自定义工具：** 内置 Excel 数据转换引擎，老师可一键导入课程知识点，快速生成专属教学游戏。
* **Teacher Customization Tools:** Includes a built-in Excel data conversion engine, allowing teachers to generate personalized educational games.

---

## 🚀 快速开始

### 1. 运行环境（Environment）
直接使用浏览器（推荐 Chrome, Edge 或 Safari）打开网页 `https://nunuzh.github.io/Catopus_Monopoly_for_Science_Learning/` 即可，无需安装任何环境。

Open the webpage https://nunuzh.github.io/Catopus_Monopoly_for_Science_Learning/ in your browser (Chrome, Edge, or Safari recommended). No local environment or installation is required.

### 2. 准备工作
* **人数：** 建议 2 - 6 组参与。
* **Group Size:** 2 - 6 groups/players are recommended.
* **设备：** 建议连接大屏幕或投影仪进行展示，由一名主持人（老师）操作界面。
* **Hardware:** For the best experience, we recommend using a large screen or projector. A host should manage the interface.
* **自定义游戏卡片内容（Customizing Game Cards）：**
    1. 点击左上角 `⚙️ 自定义`。
       Click the ⚙️ Customize icon in the top-left corner.
    2. 按照 `类型 \t 标题 \t 描述` 的格式从 Excel 粘贴内容，点击生成即可应用。【注意：类型列目前仅支持“theory”, "experiment", "phenomenon"；请注意严格区分大小写】
       Paste your content from Excel using the format: Type \t Title \t Description, than click "Generate" to apply.
       Note: The "Type" column currently only supports "theory", "experiment", and "phenomenon". Please ensure strict case sensitivity.  
    3. 准备一些独立于游戏外的问题（推荐高难度的协作型、或对抗型题目）。当某个团队停留在“同行评审”方格上时，教师揭晓其中的一道挑战题，学生们可尝试回答以赚取额外加分。
       Prepare another set of high-difficulty, collaborative or competitive questions. When a team lands on a "Peer Review" tile, the teacher reveals one of these challenges for students to earns bonus points.


---

## 🎮 游戏规则 (Gameplay)

### 阶段一：探索发掘（Discovery）
玩家通过掷骰子落在「探索」格子，选择方向（现象/理论/实验）并抽取卡牌。若回答正确/论述合理，可将卡牌收入背包，且该地块会揭晓为「空地」或「评议」。

Players move by rolling dice; if they land on an "Exploration" tile, they choose a category (Phenomenon/Theory/Experiment) and pick a card. If the answer is correct or the explanation is logical/well-reasoned, the player adds the card to their inventory. Once a card is collected, the tile reveals its true nature as either a "Land" or "Peer Review".

### 阶段二：论证占地（Argumentation）
落在「空地」时，玩家需使用手中至少两张卡牌进行逻辑串联（如：用某个实验验证某个理论）。老师和其他同学判断论证成功后，该玩家成为该地的「领主」。

When landing on a "Land" tile, players must use at least two cards from their inventory to create a logical/reasoned connection (e.g., using a specific experiment to verify a theory). Once the teacher and peers validate the argument, the player becomes the "Lord" of that tile.

### 阶段三：踢馆与巩固（Challenge）
当其他玩家落在已有领主的土地时，需缴纳“积分路费”，并可发起「踢馆」：

When a player lands on a tile already owned by a Lord, they must pay a "Point Toll" and may initiate a "Challenge":
* **挑战者：** 选择一种策略与领主的卡牌进行互动。
* **Challenger:** Selects a specific strategy (from "Coordination", "Challenge", "Inquiry", "Refer to Wider Context") to interact with the Lord's card(s).
* **领主：** 进行防守或反驳。
* **Lord:** Defends their ownership of than land by initiating new arguments or provides a counter-argument.
* **裁判：** 由全场或老师裁定，胜者获得该地块的股份，股份多者成为新领主。
* **Judgment:** The entire class or the teacher acts as the judge. The winner gains shares of that tile, and the player with the most shares becomes the new Lord.

### 阶段四：最终结算（Victory）
* **胜负标准：** 最终获胜者由总分决定，而非占领土地的数量。
* **Victory Condition**:** The winner is determined by the Total Score, not the number of tiles owned.
* **股份的功能：** 拥有“股份”可以让你成为领主并控制地块，但股份本身不计入最终胜分。
* **Role of Shares:** Shares allow you to become a "Lord" and control tiles, but they do not count as final victory points.
* **领地收益：** 成为领主的主要优势是向路过的其他小组收取“积分路费”，从而增加你的总分。
* **Land Advantage:** Being a Lord allows you to collect "Point Tolls" from opponents, which is a key way to boost your Total Score.
* **核心目标：** 通过股份统治地图只是手段，积累最高总分才是最终目的。
* **The Bottom Line:** Dominating the map is a strategy; accumulating the highest Total Score is the goal.
---

## 🎨 鸣谢与致谢 (Credits)
本项目的视觉表现力离不开视觉与角色设计创作者高蜻禅（Dido）的倾力支持！感谢她为「学术游园会」注入的独特灵魂。

The visual impact of this project owes everything to the wholehearted support of its visual and character designer, Gao Qingchan (Dido)! A big thank you to her for infusing this project with its unique soul.
