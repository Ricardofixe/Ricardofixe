<img src="assets/hero.svg" alt="Ricardo Isidro. I learn how big software works by building my own version. Currently writing my thesis on multi-agent LLMs." width="100%">

## `$ ls ~/projects`

<p>
  <a href="https://github.com/Ricardofixe/pt-ai-blockers"><img src="assets/card-pt-ai-blockers.svg" alt="PT AI Blockers: which Portuguese sites block AI crawlers. 69 sites, 17 AI bots, checked every morning." width="49%"></a>
  <a href="https://github.com/Ricardofixe/IscTorrent"><img src="assets/card-isctorrent.svg" alt="IscTorrent: peer-to-peer file sharing in Java. A 3 MB download went from 14.2 s to 0.15 s." width="49%"></a>
  <a href="https://github.com/Ricardofixe/Financial-Tweet-Sentiment"><img src="assets/card-tweet-sentiment.svg" alt="Financial Tweet Sentiment: the final model labels unseen financial tweets as bearish, bullish or neutral, with 0.866 macro-F1." width="49%"></a>
  <a href="https://github.com/Ricardofixe/genetic-painting"><img src="assets/card-genetic-painting.svg" alt="Genetic Painting: Vermeer recreated with 100 triangles by a genetic algorithm." width="49%"></a>
</p>

## `$ curl pt-ai-blockers/api/summary`

Live numbers from [PT AI Blockers](https://pt-ai-blockers.ricardofixe.workers.dev), refreshed every morning by a Cloudflare Worker:

[![Sites blocking AI training bots](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fpt-ai-blockers.ricardofixe.workers.dev%2Fapi%2Fsummary&query=%24.byPurpose.training.blocked&label=sites%20blocking%20AI%20training&style=for-the-badge&color=f38020&labelColor=0d1117&logo=cloudflare&logoColor=f38020)](https://pt-ai-blockers.ricardofixe.workers.dev)
[![Sites whose robots.txt could be read](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fpt-ai-blockers.ricardofixe.workers.dev%2Fapi%2Fsummary&query=%24.totals.known&label=sites%20readable&style=for-the-badge&color=30363d&labelColor=0d1117)](https://pt-ai-blockers.ricardofixe.workers.dev)
[![Date of the last check](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fpt-ai-blockers.ricardofixe.workers.dev%2Fapi%2Fsummary&query=%24.checkedOn&label=last%20check&style=for-the-badge&color=30363d&labelColor=0d1117)](https://pt-ai-blockers.ricardofixe.workers.dev)

## `$ cat now.txt`

- **Writing my thesis** on a multi-agent LLM system that plans how to learn any skill and adapts the plan to the learner.
