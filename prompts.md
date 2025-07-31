# LLM Prompt Testing – SU Women’s Lacrosse 2025

## Simple Prompts and Answers

---

**Q: How many games did the team play?**  
**A:** 19  
✅ Correct – Matches the team total in the dataset.

---

**Q: Who scored the most goals?**  
**A:** Emma Muchnick (34 goals)  
✅ Correct – Verified against structured table.

---

**Q: Which player had the highest shooting percentage?**  
**A:** Gracie Britton (48.8%)  
✅ Correct – From: 20 goals / 41 shots.

---

**Q: Which player had the most assists?**  
**A:** Emma Ward (46 assists)  
✅ Correct – No other player is close.

---

**Q: Which player averaged the most points per game?**  
**A:** Emma Ward (4.00 points/game)  
✅ Correct – 76 points / 19 games.

---

**Q: Which player had the most draw controls?**  
**A:** Joely Caramelli (39 draw controls)  
✅ Correct – From full stats table.

---

## Prompt Engineering Notes

- When the model was asked, *"Who had the highest SOG%"*, it sometimes hallucinated unless explicitly given the formula.
- Rewriting questions to include *"based on this table"* improved accuracy.
