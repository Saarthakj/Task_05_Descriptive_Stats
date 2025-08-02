# Task_05_Descriptive_Stats

# LLM Prompting Process & Examples

**Note:**  
All prompts, analysis, and visualizations in this project use **Syracuse University Women’s Lacrosse data from the 2024 and 2025 seasons**.

As part of this research task, I challenged ChatGPT (a Large Language Model) to answer natural language questions about the SU Women’s Lacrosse dataset using only small table snippets from these two seasons. The results were tracked for accuracy, clarity, and any required prompt engineering.

---

## Example Prompts and Results

**1. Games Played per Year**

> **Prompt:**  
> Given the following table, how many games did SU Women’s Lacrosse play in 2024 and 2025?  
> ```
> Year  Games  Wins  Losses  Home  Away  Neutral  Conference  NonConference
> 2024  22     16    6       9-2   5-2   2-2      9-1         7-5
> 2025  19     10    9       5-4   4-4   1-1      5-4         5-5
> ```

**LLM Response:**  
> In 2024, SU played 22 games. In 2025, they played 19 games.

**Result:**  
Correct. No prompt engineering needed.

---

**2. Win-Loss Record**

> **Prompt:**  
> What was SU’s win-loss record for 2024 and 2025 based on this table?

**LLM Response:**  
> 2024: 16 wins, 6 losses. 2025: 10 wins, 9 losses.

**Result:**  
Correct.

---

**3. Home vs Away Win Percentage**

> **Prompt:**  
> Based on the home and away records, did SU perform better at home or away in 2024? Show win percentages.

**LLM Response:**  
> At home: 9-2 (81.8% win rate). Away: 5-2 (71.4% win rate). SU performed better at home.

**Result:**  
Correct, with calculation.

---

**4. Toughest Opponent by Margin of Defeat**

> **Prompt:**  
> Here’s a list of 2024 game results. Who was their toughest opponent, based on the largest margin of defeat?  
> *(sample table including Apr 28 vs Boston College: SU 8, Opp 15)*

**LLM Response:**  
> Boston College on April 28 (lost 8–15, margin: –7).

**Result:**  
Correct.

---

**5. Highest Home Game Attendance**

> **Prompt:**  
> Which 2024 home game had the highest attendance, and what was the outcome?  
> *(table including Mar 16 vs #9 North Carolina, Attendance 2982)*

**LLM Response:**  
> The highest attendance was vs #9 North Carolina on March 16 (2,982 attendees). SU won 20–5.

**Result:**  
Correct.

---

**6. Coach Strategy: Offense or Defense?**

> **Prompt:**  
> Based on these yearly stats, if the coach wants to win 2 more games in 2026, should the focus be on improving offense or defense? Explain with data.  
> ```
> Year   Goals/Game   Opp Goals/Game
> 2024   15.23        9.68
> 2025   12.37        11.63
> ```

**LLM Response:**  
> Both offense and defense worsened in 2025. The bigger drop was in offense (goals/game down by nearly 3), so the coach should prioritize improving offense.

**Result:**  
Correct, logical answer.

---

## Prompt Engineering Insights

- **All questions and analysis were based strictly on 2024 and 2025 season data.**
- Simple tabular prompts led to correct answers.
- For reasoning questions, providing summary stats or clarifying what to compare led to detailed and accurate responses.
- When asked open-ended questions, the LLM sometimes needed clarification on what metric to use, especially for “most improved player” or similar queries.

---

## Conclusion

When given clear, relevant data in a small table from the 2024 and 2025 seasons, ChatGPT answered all six research questions about the SU Women’s Lacrosse season accurately and logically, requiring little to no additional prompt engineering.

---
