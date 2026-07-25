KEYLOCK — VOCAL PITCH GAME

WHAT IT DOES
- Target Notes: randomly chooses notes from your selected key and listens until you sing and hold the exact note.
- Free Sing: listens for 30 seconds and reports what percentage of stable detected notes belong to the selected key.
- Shows the detected note, frequency, cents flat/sharp, mic level, pitch clarity, score, streak, history, XP, and saved best progress.
- Audio is processed locally in the browser. It is not uploaded or recorded.

FASTEST WAY ON A COMPUTER
1. Install Node.js if it is not already installed.
2. Open Terminal / Command Prompt inside this folder.
3. Run:
   node server.js
4. Open:
   http://localhost:8787
5. Allow microphone access.

PHONE / IPHONE
Mobile browsers require the page to be served through HTTPS before microphone access is allowed reliably.
Upload index.html to an HTTPS host such as GitHub Pages, Netlify, or Vercel, then open that link in Safari.
Opening the raw HTML file directly from the Files app may block microphone permission.

TIPS
- Use a sustained vowel such as “ah” or “oo.”
- Keep the phone or microphone a consistent distance from your mouth.
- Use headphones when pressing Hear Target so the reference tone does not leak into the microphone.
- Normal difficulty accepts ±30 cents and requires a 0.75-second hold.
- Free Sing checks scale membership. It does not judge whether a note fits a specific chord at that exact moment.


HEALTHY ATTEMPT
- Target Notes judges how the note was reached and held, not only whether it was correct.
- It can flag shaky holds, consistently flat or sharp pitch centers, sliding into the note, and possible pushing.
- The pushing warning is an audio-based clue, not a medical diagnosis. Stop if singing hurts.
