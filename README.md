# AI Career Counsellor

Persona-based AI Career Counsellor built according to the supplied assignment brief.

## Files
- `index.html` — complete HTML, CSS and JavaScript in one file.
- `README.md` — project documentation.

## Personas
1. Technical Career Counsellor
2. HR & Placement Counsellor
3. Academic & Research Counsellor
4. Entrepreneurship Counsellor

## Six Prompt Card Elements
Every persona defines:
- Role
- Audience
- Context
- Format
- Constraints
- Language

## Gemini Integration
The selected personas and user question are combined into one structured prompt and sent through one Gemini `generateContent` request. Responses are displayed separately for comparison.

## API Key
The source code contains no API key. Enter a key only at runtime. Never commit a real key to GitHub.

## Run
```bash
python3 -m http.server 8000
```
Open `http://localhost:8000`.

## Sample Questions
- Should I prepare for placements or pursue higher studies?
- I know Python but do not have any projects. What should I do?
- Should I become an AI Engineer, Data Scientist or Software Developer?

## GitHub Structure
```text
project/
├── index.html
├── README.md
└── assets/
```

Add your screenshots and other evidence under `assets/` before final submission.

## Demo Video
Show:
1. Interface
2. Personas
3. One-persona question and response
4. Multiple-persona selection
5. Same question
6. Separate responses
7. Comparison
8. Prompt Card and one-request flow
