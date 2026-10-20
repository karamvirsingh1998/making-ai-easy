# Making AI Easy

Interactive, beginner-friendly explainers for the ideas behind modern AI. Each lesson starts with plain-language pictures and analogies, then goes all the way to the real math.

**Live site:** https://karamvirsingh1998.github.io/making-ai-easy/

## Lessons

| # | Lesson | Pages |
|---|---|---|
| 1 | **Attention Is All You Need** (Vaswani et al., 2017) | [Blog post](attention-is-all-you-need/blog.html) · [Beginner picture book](attention-is-all-you-need/beginner.html) · [Live math simulation](attention-is-all-you-need/attention-engine.html) |

More lessons coming soon.

## How it's built

Every page is a single self-contained HTML file with no build step. Open `index.html` in a browser, or run:

```bash
python3 -m http.server 8000
```

## Accuracy notes (Lesson 1)

- The simulation computes embeddings, positional encoding, Q/K/V, attention scores, softmax, multi-head attention, residuals, the encoder stack and masking live with the paper's formulas, using random untrained weights.
- Cross-attention weights, next-word probabilities and the training-loss panel use illustrative values typical of a trained model, and each stage says so.
- BLEU scores and training costs come from Table 2 of the paper. The learning-rate schedule is the paper's exact formula.

## Author

Karamvir Singh
