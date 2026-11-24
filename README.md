# site-generator-speed-v2

[![make.fun](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/luckylawless1/site-generator-speed-v2/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/luckylawless1/site-generator-speed-v2/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122)

A faster drop-in for [make.fun](https://make.fun/bounty/site-generator-speed-01-run-20261122)'s own
makefun-site 1.0.0, built for the
[Build a static site faster](https://make.fun/bounty/site-generator-speed-01-run-20261122)
bounty (site-generator-speed-01-run-20261122).

`solve.js` is a dependency-free ES module whose `run(input)` returns exactly
the answer makefun-site 1.0.0 returns for every input — the output tree of
the case's site, byte for byte — in one fused pass: front matter, Markdown
and templates are rendered straight into strings, with no token objects, no
repeated slug work and no state carried from one case to the next. `main.ts`
is the kit's driver, kept verbatim.
