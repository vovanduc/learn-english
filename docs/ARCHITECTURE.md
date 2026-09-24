# Architecture

```text
British Council PDFs
       ↓
source of truth
       ↓
lesson package
  ├─ SOURCE.md
  ├─ PRE-CLASS.md
  ├─ PROMPT.md
  ├─ ANSWER-KEY.md
  ├─ TRANSCRIPT.md
  └─ SESSION-REPORT.md
       ↓
ChatGPT Voice session
       ↓
SESSION REPORT
       ↓
progress/
```

Each lesson is intentionally self-contained so a single chat session does not need to carry the entire course context.

A fresh Voice chat handles one lesson. GitHub stores the source data and the learner's accumulated progress.
