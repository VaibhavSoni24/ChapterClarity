# ChapterClarity

A free, static, browser-only English readability helper. It estimates Flesch Reading Ease and Flesch-Kincaid grade level, then highlights the five hardest sentences using sentence length, estimated syllables, complex-word ratio, and long-word ratio.

## Run locally
Open `chapterclarity.html` in a modern browser. No dependencies, API key, account, or backend is required. Text is processed in the browser.

## Publish for free on GitHub Pages
1. Create a new public repository on GitHub (for example, `chapterclarity`).
2. Upload `chapterclarity.html` and rename it to `index.html`.
3. Open the repository Settings → Pages. Choose publishing from the `main` branch and the `/ (root)` folder, then save.
4. Wait for the Pages build to finish; GitHub will show the public website URL under Settings → Pages. Open it in a private browser window and test it before putting the URL in an application.

Official guide: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Limitations
This is an approximate, English-only tool. Syllable counts are estimated using spelling rules, sentence boundaries are detected from punctuation, and “hardest” is a transparent heuristic rather than an AI judgement. It cannot assess meaning, tone, context, genre, or audience. Test on real chapters before making strong editorial claims.
