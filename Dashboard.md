
## Quick Links
- [Email](https://mail.google.com/)
- [Classroom](https://classroom.google.com/)
- [Notes (Keep)](https://keep.google.com/)
- [Calendar](https://calendar.google.com/)
- [VTOP](https://vtop.vitbhopal.ac.in/vtop/login)
- [Notion](https://www.notion.so/)

---

## Deadlines
> Add tasks anywhere with due dates; they show here. Example:
> - [ ] Exam registration (Odd Sem) 📅 2025-09-20 ⏳ 2025-09-10 #registration program::BTech-CS

### Due Today
not done
due on today
group by filename
sort by priority desc
sort by due

text

### Next 7 Days
not done
(due after today) AND (due before in 7 days)
group by due
sort by due

text

### Overdue
not done
due before today
group by due

text

---

## Today's Focus
- Top 3
  - [ ] 
  - [ ] 
  - [ ] 

not done
(priority is high)
hide backlink
limit 10

text

> Hint: add 🔼 for high priority in Tasks. Example: "- [ ] DAA assignment 🔼 📅 2025-09-10"

---

## To-Do
not done
no due date
group by filename

text

> Program queues (optional tokens inside task text):
- BTech CS
not done
(description includes "program::BTech-CS")
group by filename
sort by due

text
- BS Data Science
not done
(description includes "program::BS-DS")
group by filename
sort by due

text

---

## Pomodoro
- Session length: 25 min • Short break: 5 min • Long break: 15 min
- Cycles today: 
  - [ ] Pomodoro 1
  - [ ] Pomodoro 2
  - [ ] Pomodoro 3
  - [ ] Pomodoro 4

> Tip: Use a timer app; check cycles here to track completed sessions.

---

## Notes
- Quick capture
  - [ ] 
  - [ ] 
- Scratchpad
  - Write ideas, meeting notes, or references below.

---

## Words
> Daily word or quote. Replace the seeds below.

- “Discipline is choosing what you want now vs. what you want most.”
- “Amor fati.”
- “Focus on inputs; outcomes will follow.”

---

## Registration Windows (optional Dataview)
TABLE file.link AS Item, window_start, window_end, program, semester
FROM ""
WHERE contains(file.tags, "registration")
SORT window_start asc

text

## Recently Completed (7 days)
done on or after yesterday - 6 days
sort by done reverse

text
undefined
Notes:

Quick Links mirror the six links in the HTML; add or remove as desired.

“Deadlines” replaces the HTML date-input UI with Tasks queries that auto-collect due and scheduled items from the vault.

Pomodoro is manual checkboxes since Markdown doesn’t run timers; mark completed cycles to emulate the original timer card.