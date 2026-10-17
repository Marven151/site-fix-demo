# site-fix-demo

Before and after of a typical small-business website, made to show the kind of fixes I do on existing sites. The business (a bakery) is fictional, the problems are the ones I meet most often.

**Live:** https://marven151.github.io/site-fix-demo/

- `before/` is deliberately broken: fixed 980 px layout with no mobile setup, no character encoding (Polish letters turn into garbage), 4.9 MB of unoptimised photos, a form that posts to a page that does not exist, light grey text, no alt texts.
- `after/` is the same content, fixed.
- `index.html` compares the two, with Lighthouse scores and a list of what changed.

| Lighthouse (mobile) | Before | After |
|---|---|---|
| Performance | 75 | 99 |
| Accessibility | 45 | 100 |
| Best practices | 88 | 100 |
| SEO | 82 | 100 |
| Page weight | 4.9 MB | 303 KB |

Single local run of Lighthouse 13 with simulated throttling; repeat runs vary by a few points.

Photographs: Dana Hutchinson (CC BY 3.0), Faisal Ahammad (CC0), Mmangan333 (CC BY-SA 4.0).
