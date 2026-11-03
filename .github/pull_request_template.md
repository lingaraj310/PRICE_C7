## Pull Request: Retail AI Submission

### Team Information
- Team Number: Team 5
- Project Name: The Empathy Engine
- Track Category: Natural Language Processing & Customer Emotion Analytics
- Team Members:
  - Member 1: Lingaraj V (@lingaraj310)
  - Member 2: Nandhini J (@Nandhini-187)
  - Member 3: Nisanth EP (@nisanthofficial00-ai)
  - Member 4: Ahil VP (@ahil-ahil)
  - Member 5: Kaviya M (@Kaviyamathi876-lab)

---

### Problem and Solution Overview
- Core Problem Solved: Eliminates the star-rating blindspot in retail feedback by transforming qualitative customer feedback into distinct emotional dimensions.
- Target Customer: Customer Experience (CX) Directors & Retail Operations Managers.
- Key Features Implemented: Dual-engine NLP analysis (deterministic lexicon + Gemini 2.5 Flash AI), CX Friction Index %, Satisfaction Rate %, Plotly charts, filterable inspector, and automated action plan generation.

---

### Prompt Log and Execution Strategy
Document the prompts used during development:

1. Initial Architecture Prompt:
   > "Design a dataset of 30 realistic qualitative retail customer reviews reflecting multi-touchpoint customer experiences..."

2. Core Algorithm and Math Prompt:
   > "Implement an NLP analytics engine in Python (empathy_engine.py) with functions load_reviews, analyze_review, compute_emotion_distribution..."

3. UI and Interactivity Prompt:
   > "Build an interactive, production-ready Streamlit dashboard (app.py) formatted in clean academic dark theme with zero emojis..."

4. Debugging and Edge Case Handling Prompt:
   > "Develop a comprehensive Pytest test suite in tests/test_team05.py to validate algorithm correctness and edge cases..."

---

### UI Preview
Attach screenshots demonstrating the application running locally via `streamlit run app.py`:

- [x] Interactive Dashboard / Controls
- [x] Output / Charts / Result Cards

---

### Self-Evaluation Checklist (100 Points / 25 Marks)
- [x] Architecture (20 pts): Folder structure clean, app.py, engine file, README.md, requirements.txt present.
- [x] Logic and Unit Tests (30 pts): All tests in tests/ pass with pytest.
- [x] UI Readiness (20 pts): Interactive Streamlit UI functions with all required widgets, charts, and metrics.
- [x] Data Quality (15 pts): Datasets conform to column and row volume requirements.
- [x] Documentation (15 pts): Team README has all sections filled including the Prompt Log.
- [x] Local Autograder Ran: Ran python evaluator/autograder.py --team 5 and verified score.
