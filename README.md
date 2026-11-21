# IM Exam Room Finder

A one-page site that tells students which room to go to for the IM final exam. Type your surname and it shows your room:

- Surnames starting A to P: **IN-0B60**
- Surnames starting Q to Z: **HG-KC07**
- Students with extra time: **HG-KC07**, no surname needed

Accents are stripped before the first letter is read, so Muller and Müller land in the same room. A rotating quote and a bit of confetti come with the answer.

Live at [room-im-exam.vercel.app](https://room-im-exam.vercel.app).

## Run it

Everything lives in `index.html` (HTML, CSS and vanilla JavaScript, no build step, no dependencies). Open the file in a browser, or serve the folder:

```bash
npx serve .
```

## Deploy

The site is a static Vercel project (`room-im-exam`). Deploy with `vercel --prod` from this folder.
