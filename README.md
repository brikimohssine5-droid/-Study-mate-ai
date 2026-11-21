# StudyMate AI

An open-source, multilingual study companion for learners. StudyMate helps students organize revision, turn lesson text into flashcards, and practice with quick quizzes.

> **Current status:** lightweight browser-based MVP. It works locally in your browser and does not require an API key. AI-powered summaries and integrations are planned, not yet implemented.

## Features
- Create, edit, and delete study notes.
- Generate simple flashcards from pasted lesson text.
- Build a quick multiple-choice practice quiz from text.
- Track revision tasks and completion.
- Arabic, French, and English interface labels.
- Local-first storage using browser localStorage.

## Run locally
1. Clone or download this repository.
2. Open `index.html` in a modern browser.
3. Your notes and tasks stay in that browser on that device.

No build step or dependencies are required.

## Roadmap
- [ ] Improve Arabic and French text processing.
- [ ] Add import/export for notes and flashcards.
- [ ] Add accessible keyboard navigation.
- [ ] Add automated tests.
- [ ] Explore optional AI-provider integrations with clear privacy controls.

## Contributing
Issues and pull requests are welcome. Please describe the problem, the proposed change, and how you tested it. See [CONTRIBUTING.md](CONTRIBUTING.md).

## Privacy
The current MVP stores data in the browser's localStorage. It does not send lesson content to a server.

## License
MIT. See [LICENSE](LICENSE).
