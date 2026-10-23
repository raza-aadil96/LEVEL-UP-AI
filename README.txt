LEVEL UP AI
===========

A self-contained browser app for first-year B.Tech CSE AI/ML students. It combines a quiz practice tool and a resume-to-job skill matcher.

RUN ON WINDOWS
--------------
1. Extract the downloaded ZIP file.
2. Open the level-up-ai folder.
3. Double-click index.html. It opens in your default browser.

No installation, internet connection, account, or API key is required. The app works from a local file. Progress counts and recent activity are stored in this browser on this device. Resume and job text are analyzed in the page and are not saved or uploaded.

FEATURES
--------
- Curated multiple-choice question bank for C, Python, Machine Learning, and GenAI.
- Easy, medium, and mixed practice, with progress, scoring, explanations, retry, and local progress tracking.
- Resume/job text comparison with skill overlap, missing skills, and practical suggestions.
- Responsive layout, keyboard-visible focus, accessible status messages, and input validation.
- No external dependencies. The optional LLM integration point is documented in index.html. For real use, connect a trusted backend endpoint; never place a secret API key in browser JavaScript.

LIMITATIONS
-----------
The quiz questions are from a local curated bank; they are not dynamically generated. Resume matching uses a transparent built-in keyword list, so it may miss synonyms and context. Its overlap score is not a hiring prediction.
