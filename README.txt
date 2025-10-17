LoanBot Chat UI - Demo (Round 1)
=================================

This is a static, single-file demo of the LoanBot chat UI built for Techathon Round 1.

Features:
- Dark, modern theme using TailwindCSS and glassmorphism
- Chat area with mocked conversational flows
- Adaptive nudges (clickable chips)
- Explainable Decision Trace UI panel (Why? and Audit buttons)
- File upload simulation (salary proof -> OCR simulated)
- Admin / Audit placeholders for demo

How to run:
1. Download and unzip the package.
2. Open 'index.html' in a modern browser. (This demo uses CDN links for React and Tailwind.)
3. Interact with the chat, try samples like:
   - I need a personal loan of 200000
   - Upload a salary file (use any file)
   - Click the chips on the left to try smart nudges

Notes:
- This is a frontend-only mock meant for prototyping and PPT screenshots.
- Backend orchestration, FastAPI endpoints and real AI are not implemented in this static demo.
