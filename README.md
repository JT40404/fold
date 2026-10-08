# Fold

Static site for $FOLD. Creator fees fund cloud GPU time for protein simulations on cancer-related targets, plus Claude API credit to analyse the results.

## Launch checklist
- Open `index.html`, find `ca: ""` in the `FOLD` block, and paste the token contract address.
- Set each GPU's `online` time in the `gpus` list to when it actually started, and update `nsPerDayPerGpu` with your measured simulation speed.
- Commit and push. Vercel redeploys automatically.
