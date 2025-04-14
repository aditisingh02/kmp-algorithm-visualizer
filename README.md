# KMP Algorithm Visualizer

A visual tool to understand how the Knuth-Morris-Pratt (KMP) string matching algorithm works in real time.

🔗 [Live Demo](https://kmp-algorithm-visualizer.vercel.app/)

---

## Features

- Visualize the pattern preprocessing step (LPS array generation)
- Step-by-step animation of pattern matching in the text
- Highlights matches, mismatches, and LPS jumps
- Clean, interactive UI for better understanding

---

## About KMP

The Knuth-Morris-Pratt (KMP) algorithm is an efficient string matching technique that avoids redundant comparisons by preprocessing the pattern using the LPS (Longest Prefix which is also Suffix) array. This visualizer helps demonstrate how KMP uses the LPS array to achieve linear time matching.

---

## Tech Stack

- React
- Tailwind CSS
- TypeScript (if used)
- Deployed on Vercel

---

## Getting Started

To run the project locally:

```bash
git clone git@github.com:aditisingh02/kmp-algorithm-visualizer.git
cd kmp-algorithm-visualizer
npm install
npm run dev
```
