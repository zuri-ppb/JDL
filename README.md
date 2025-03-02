# MR Student Life Simulation Game Development - JDL Model Design

## Model Design Key Points

1. **User**
- Contains basic attributes (level, experience, energy, money, etc.)
- Has background story, dormitory anchor information
- Stores item inventory and ranking data through association tables

2. **Task**
- Designed a variety of task types (daily, main line, branch line, social, learning)
- Contains trigger conditions, completion conditions and reward settings
- Supports pre-task requirements and cooling time design

3. **Item**
- Covers attributes such as name, type, rarity, effect
- Contains usage restrictions (durability, cooling time)
- Supports game mechanisms such as trading and stacking

4. **MiniGame**
- Supports a variety of game types (multiple choice questions, connection questions, etc.)
- Contains questions, answers, explanations and rewards
- Records user game scores

5. **Leaderboard**
- Support multiple types of rankings (academic, social, wealth, etc.)
- Implement a season system that can be reset regularly
- Include ranking and reward mechanisms

6. **Log**
- Record various events
- Include timestamp and location information
- Facilitate data analysis and game playback

7. **Region**
- Include MR anchor data
- Design interactive objects
- Support region 
locking conditions and adjacent region associations

![studentgame](https://github.com/user-attachments/assets/debeb517-5c34-4d0f-bdd8-5a6348fe3714)

