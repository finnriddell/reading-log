# Reading log

**Live site:** https://finnriddell.github.io/reading-log/

Every article I read from the FT, The New Yorker, The Economist, Wired, NOEMA and others, scored from 1 to 5 on interest, importance and style, with a short takeaway written straight after reading. The site shows the whole log as a pile of bubbles: bigger means a higher score, newest at the top, and colour shows the subject. Scroll down for my top reads and the full, searchable list.

## Why I keep it

To read more deliberately and to sharpen my own analysis and writing. It is also a small pool of human judgement: the writing is world class, the judgement is messy and human, and that may matter more as information gets swamped by machine-generated ideas, conclusions and writing.

## How it works

1. **A Google Sheet** holds one row per article.
2. **A capture page** (private, Google Apps Script): I paste or share a link from my laptop or phone, it fills in the source, author, date and title, and I add my takeaway and score.
3. **A read-only data feed** (public, Google Apps Script) sends only the articles I've marked public. My private notes never leave the Sheet.
4. **This website** (`index.html`, hosted free on GitHub Pages) reads that feed and draws the bubbles and the list in the browser.

It costs nothing to run, uses no API keys, and has no AI inside it. Every score and takeaway is mine.

## How it was made

I designed and directed the project, set the rules, chose the design and tested every change on my own laptop and phone. The code was written with Claude, an AI model, under my direction. The commit history here shows how the site has changed.

---

© 2026 Finlay Riddell. All rights reserved. The reading notes, scores and takeaways are my own writing. The site's code may be viewed but not reused without permission; get in touch if you'd like to use any of it.
