# ChapterLens

A free, browser-only readability checker for authors.

## What it does
- Calculates Flesch Reading Ease
- Shows word and sentence counts
- Ranks the five hardest sentences using sentence length + estimated syllable density
- Does not upload the pasted chapter

## AI/tools used
ChatGPT was used to help design and implement the prototype. The readability calculation and ranking logic are deterministic JavaScript so the core result can be checked rather than blindly trusting an AI model.

## Honest limitation / test note
The first prototype used an AI-suggested syllable-counting approach. English syllable counting is imperfect for words with unusual spellings, names, abbreviations and punctuation. The current version therefore labels syllables as "estimated" rather than presenting them as ground truth.

## How to publish
Upload `index.html` to any static web host such as GitHub Pages, Netlify, or Vercel. No backend is required.
