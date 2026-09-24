# English Voice Coach — Zero → A2 (with future B/C expansion)

A GitHub-based, lesson-by-lesson English listening and speaking program for a Vietnamese beginner. The learning flow is designed for separate ChatGPT Voice sessions, one lesson per chat, with GitHub as long-term memory and source control.

## Source of truth

The primary curriculum is the two provided British Council A1+A2 listening workbook PDFs stored under `source/british-council/`. The workbook contains 28 listening tests: 15 A1 and 13 A2. Do not silently replace or reorder this curriculum.

For additional or future-level materials, use the Google Drive source library recorded in `source/RESOURCE-LIBRARY.md`. This library may contain B1/B2/C1/C2 materials for future expansion.

External audio/video is supplementary only.

## Source hierarchy

1. Lesson-specific source files in this repository
2. Original materials in the Google Drive source library
3. Explicitly approved supplementary external resources

## Session model

`PRE-CLASS` → `VOICE SESSION` → `SESSION REPORT` → `progress/`

Each lesson has its own package. The learner copies only `PROMPT.md` into a fresh ChatGPT Voice chat. Teacher data (exercise, answer key, transcript) stays in the repo and is revealed progressively during the session.

## Rules

- Listening and speaking are the primary objectives.
- Do not reveal answer keys or transcript before the learner attempts the relevant listening task.
- Correct only the most important 1–2 errors at a time, then force repetition and transformation.
- Increase difficulty based on demonstrated comprehension and speaking performance, not calendar time alone.
- End every session with a structured report that can be pasted back into the repo.
- Preserve the original source's level, ordering, terminology, exercise structure, transcripts, answer keys, and links.
- Do not silently replace source material with unrelated material.

## Lesson generation

Detailed lesson packages are generated incrementally. `GENERATION-QUEUE.md` tracks what is scaffolded, complete, and ready for study.

## Future expansion

Current implementation: A1 → A2.

Future source tracks: B1 → B2 → C1 → C2, using materials actually present in the Google Drive source library or explicitly provided files.
