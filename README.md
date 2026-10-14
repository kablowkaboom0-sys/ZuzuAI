# ZuzuAI v1.0

A self-contained study companion. Open `index.html` in a modern browser or deploy it on a static web host.

## Features
- Paste study notes or import `.txt`, `.md`, `.csv`, or `.json` text files.
- Split notes into indexed passages and store them in browser IndexedDB.
- Ask questions; ZuzuAI ranks relevant passages, quotes them, and names the source notes.
- Export/restore your knowledge library as a JSON backup and delete notes.
- No CDN, external API, account, or server required.

## Important limitations
This first version is **retrieval-based**, not a trained language model: it selects relevant passages from your notes rather than generating novel explanations. Its matching is keyword-based and can miss paraphrases or select irrelevant passages. Check the cited notes. Data is local to each browser/device, not synchronized across devices; use Export backup to preserve it. Only import files you trust and avoid uploading personal/sensitive information to public repositories. PDF, Word, scanned pages, and images are not supported yet. Browser storage may be cleared by private browsing or device policies.

## Getting started
Open the page, enter a title, paste notes, press **Analyse & save notes**, then ask a question in the chat. You can also import supported text files. Export backups regularly.
