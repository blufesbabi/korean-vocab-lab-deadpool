Korean Vocab Lab · Merc Mode — Cinematic Combat Feedback

To preview: open index.html in a modern browser with the assets folder beside it.

Cinematic feedback assets:
- assets/merc-feedback-target-lost.webp
- assets/merc-feedback-contract-confirmed.webp
- assets/merc-hangul-brush.woff2 (locally bundled Korean brush font for consistent mobile/desktop rendering)
- assets/FONT-LICENSE-UNFONT.txt (font license and copyright notice)

The template artwork is static, while the Korean vocabulary and Indonesian meaning are rendered as dynamic text from each active question. The same two templates work across Quiz, Typing, Listening, Memory Lab, and the shared Custom Study feedback path without baking one word into every answer image.

On both mobile and desktop, Hangeul and its Indonesian meaning are overlaid inside the template's intel panel. The mobile layout preserves the artwork's original aspect ratio, positions text inside its frame, and uses a locally bundled Hangul brush font so the style does not depend on a device font or a Google Fonts network request.

The transparent question progress companion image remains at assets/question-progress-companion.png. Existing learning/scoring logic and app assets are preserved; the mobile cinematic feedback layout/font and answer-state visibility/restoration are the relevant changes in this revision.
