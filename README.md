# Has Katherine Given Birth?

A tiny static site hosted on GitHub Pages.

**Live site:** https://haskatherinegivenbirth.com/

## How to flip the answer (NO → YES)

The answer is stored in [`answer.txt`](answer.txt) — it contains a single word: `NO` or `YES`.

**Easiest way (browser, even from your phone):**

1. Open this direct edit link: https://github.com/jonathanbakley/KatherinesSite/edit/main/answer.txt
2. Change `NO` to `YES`
3. Click the green **Commit changes** button

The site updates within ~30 seconds (open tabs auto-refresh too).

That's it — you never need to touch `index.html`.

## How to add the baby's weight (only shows once the answer is YES)

The weight is stored in [`weight.txt`](weight.txt). It's empty by default, so nothing
shows until you fill it in.

1. Open this direct edit link: https://github.com/jonathanbakley/KatherinesSite/edit/main/weight.txt
2. Type the weight, e.g. `7 lbs 4 oz` (also accepts `7 4` or `7lb 4oz`)
3. Click the green **Commit changes** button

The weight appears under the **YES** within ~30 seconds. While the answer is `NO`,
the weight stays hidden even if this file has something in it.
