# Fuzzy Logic Assignment Prioritizer

**SCSE3103 Cognitive Computing – Group 1**
Semester V, Session 2026/2027 · Faculty of Computing, Universiti Teknologi Malaysia

## About
UTM students often manage several assignments at once and struggle to decide which one to
start first. A deadline list shows what is due soonest, but ignores how long each task takes
and how much it is worth.

This project builds a fuzzy logic system that ranks assignments using three inputs:

| Input | Range | Linguistic terms |
|---|---|---|
| Days to deadline | 0–14 days | Near, Moderate, Far |
| Estimated effort | 0–20 hours | Low, Medium, High |
| Grade weightage | 0–40 % | Low, Medium, High |

**Output:** a priority score from 0 to 100 (Low, Medium, High), with the rules that fired
shown so students can see why each assignment was ranked where it is.

## Planned tech stack
- Python 3.10 + scikit-fuzzy (fuzzy inference engine)
- Streamlit (web interface)
- SQLite (local storage)
- Plotly (priority charts)

## Team
| Member | Role |
|---|---|
| Ching Leong Chen | Project management |
| Fan Yujie | System architecture, testing and evaluation |
| Alvannur Khoir Tsauri | Data / knowledge engineering |
| Anas Ahmed Hisham | Implementation |
| Zahra Aulia Putri | Documentation and submission |

## Status
Proposal stage (Nov 2026). Design due 21 Dec 2026; prototype and final report due 21 Jan 2027.

## Workflow
- `main`: stable,
