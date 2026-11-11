# CSE Study Hub

A React + Vite + Tailwind semester study workspace for seven B.Tech CSE subjects.

## Run locally

1. Install Node.js LTS.
2. Extract this ZIP.
3. Open a terminal in the project folder.
4. Run `npm install`
5. Run `npm run dev`
6. Open the local URL printed by Vite (usually http://localhost:5173).

## Deploy

This is a static Vite site. Both providers build the app with `npm run build` and serve the generated `dist/` folder. SPA fallback rewrites are configured for direct URL visits.

### Vercel

1. Import the project folder/repository in Vercel.
2. Keep the project root at the folder containing `package.json` and `vercel.json`.
3. Vercel reads `vercel.json` to build the app and publish `dist/`.

### Render

1. Create a **Blueprint** from the project folder/repository.
2. Render reads `render.yaml` to create a static site and publish `dist/`.

No environment variables or backend service are required for the current browser-only app.

## How to study

1. Choose a subject from the sidebar or dashboard.
2. Choose a unit from the unit list.
3. Read the unit overview and expand each topic under **Read unit notes**.
4. Open **Practice Zone** and answer the unit questions.
5. Mark the unit/practice complete. Progress and written answers are saved in this browser.

## Included

- Seven subjects; Communication Skills for Engineers II is split into Aptitude and Communication tracks.
- Unit-by-unit navigation, topic notes, exam tips and unit-specific practice prompts.
- Browser localStorage progress and answer saving.
- Uploaded course resources linked in the relevant subject pages.
- Responsive desktop and mobile layout.

## Accuracy note

The topic guides are concise study explanations organised around the captured syllabus outlines. Use the linked PDFs and official course documents as the final authority for exact unit coverage, teacher-specific emphasis and answer depth. Some subjects have additional notes/question banks still to be incorporated. DCN syllabus labels and a few provisional outlines should be checked against the official file before exam use.

## Detailed unit-wise PDF notes

- The `public/resources/unit-notes/` folder contains **45 separate PDFs**.
- Every unit PDF is exactly **5 pages** and includes syllabus coverage, concise explanations, an application framework, revision points and exam-style self-test questions.
- In the website, open a subject, choose a unit, select **Study Notes**, and click **Download 5-page PDF notes**.
- Communication Skills is split into two tracks: Aptitude and Communication.
- Additional course-pack/syllabus PDFs are included for DSA, Emerging Technology and Communication Skills.

## DCN notes update (11 Nov 2026)

- Units 1–5 now have five-page PDF notes prepared using the uploaded handwritten class-note PDFs as the primary reference.
- The original uploaded class-note PDFs are included under `public/resources/dcn-class-reference/` and linked from the DCN resource list.
- The DCN Unit 6 guide remains based on the existing syllabus outline only because no Unit 6 class-note PDF was supplied.
- To open the notes: select Data Communication & Networking → choose Unit 1–5 → Study Notes → Download 5-page PDF notes.