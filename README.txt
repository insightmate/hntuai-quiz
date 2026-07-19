THE #HowNotToUseAI DIAGNOSTIC — LOCAL TEST BUILD
================================================

HOW TO USE
----------
1. Unzip this folder anywhere.
2. Open  index.html  in a normal browser (Chrome, Firefox, Safari, Edge).
   Works fully offline. (With internet it also loads three display fonts;
   without, it falls back to clean system fonts — layout is identical.)
3. Take the quiz. At the end press "See your full result page" — you'll land
   on your archetype's page with YOUR real numbers filled in (marker positions,
   the two headline %s, and the live-edge line).
4. Or click "preview all 17 result pages" (top of the quiz, or gallery.html)
   to open any page directly. Opened that way a page shows its built-in
   engine example, not your numbers.

WHAT THIS IS
------------
A self-contained preview of the whole flow — quiz -> result page — running as
plain static files, so you can feel the end-to-end before any live deployment.
It uses the real engine, the real connector, and the real wired pages.

WHAT IT IS NOT (yet)
--------------------
- Not deployed. This is a local preview; the hosted quiz.hownottouseai.com seam
  is still to be built.
- The quiz look is not final (per your own notes).
- The live-edge sentence variants still need the voice-gate pass.
- The "View the Sovereignty Matrix" button is a Phase-3 placeholder.

FILES
-----
index.html    the quiz (self-contained: React + engine inlined; hands off to a page)
gallery.html  a menu to open any of the 17 pages directly
pages/        the 17 wired result pages (unchanged from the bundle)

Note: the quiz -> page hand-off uses the browser's sessionStorage (the real
connector's transport). That works when opened as local files; it's the same
mechanism the eventual hosted version will use.
