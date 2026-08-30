<div align="center">

<img src="./ascii.svg" width="460" alt="Raghav Rege"/>

<img src="./stats.svg" width="620" alt="Contributions in the last year"/>

[github](https://github.com/rarerege) &nbsp;·&nbsp;
[linkedin](https://www.linkedin.com/in/raghav-rege/) &nbsp;·&nbsp;
[email](mailto:raghav.rege@gmail.com)

</div>

<img src="./hd-about.svg" width="620" alt="about"/>

> B.Tech CS (Blockchain Technology) @ SRMIST &nbsp;·&nbsp; Blockchain Research Intern @ Samsung Prism.<br>
> Small, sharp systems over big vague ideas.

AI/ML and backend engineer shipping production systems end-to-end — two publicly<br>
deployed AI APIs, a Solana NFT marketplace on devnet, and research presented at an<br>
international conference. Currently building<br>
[mandate-gateway](https://github.com/rarerege/mandate-gateway), a merchant-side<br>
authorization layer for AI shopping agents.

<img src="./hd-stack.svg" width="620" alt="stack"/>

<samp>python &nbsp; java &nbsp; rust &nbsp; javascript &nbsp; solidity &nbsp; fastapi &nbsp; scikit-learn &nbsp; xgboost &nbsp; postgresql &nbsp; docker &nbsp; solana</samp>

<img src="./hd-projects.svg" width="620" alt="projects"/>

**[sentiment-analysis-api](https://github.com/rarerege/sentiment-api)** &nbsp;·&nbsp; <samp>python, fastapi, xgboost</samp><br>
Production ML inference behind Redis caching — under 15ms on a cache hit,<br>
84.8% accuracy and 0.92 ROC-AUC on a 50,000-review IMDB benchmark.

**[rag-document-qa-api](https://github.com/rarerege/rag-qa-api)** &nbsp;·&nbsp; <samp>python, fastapi, langchain</samp><br>
Retrieval-augmented QA over uploaded PDFs, answers grounded in cited<br>
passages, with token-by-token streaming over WebSocket.

**solana-nft-marketplace** &nbsp;·&nbsp; <samp>rust, anchor, solana</samp><br>
NFT marketplace shipped to devnet as the reference implementation for<br>
comparative Sui / Aptos / Solana research at Samsung Prism.

**[mandate-gateway](https://github.com/rarerege/mandate-gateway)** &nbsp;·&nbsp; <samp>python, fastapi</samp><br>
Decides whether a merchant should honor an AI shopping agent's order —<br>
signature verification, reputation scoring, policy engine, zero LLM calls<br>
in the decision path.

<img src="./hd-stats.svg" width="620" alt="stats"/>

<div align="center">

<img src="./streak.svg" width="620" alt="Current and longest streak"/>

<img src="./langs.svg" width="620" alt="Top languages by bytes and by repo"/>

<img src="./year.svg" width="620" alt="The last year, one character per day"/>

</div>

<img src="./hd-about-this-page.svg" width="620" alt="about this page"/>

Every graphic on this page is generated inside this repository, not pulled<br>
from someone else's server. `ascii.svg` is a photo pushed through a<br>
character ramp by [`scripts/make_portrait.py`](scripts/make_portrait.py);<br>
the stat graphics and the section headings are drawn by<br>
[a scheduled action](.github/workflows/stats.yml) straight from the GitHub<br>
GraphQL API, once a day, committing only what changed.

They animate with SMIL inside the SVG, because GitHub strips scripts from<br>
READMEs — and since nothing loads from a third party, nothing here can<br>
rate-limit or go dark. The headings are SVGs for the same reason: GitHub<br>
also strips CSS, so an image is the only way to put this page's own<br>
typeface on them.

The typeface is [JetBrains Mono](scripts/fonts), subset to just the<br>
characters each graphic draws and inlined as base64 — the portrait's grid<br>
assumes an advance width of exactly 0.600 em, and a viewer whose default<br>
monospace is narrower would otherwise see it squeezed.

Language totals cover public repositories only. `year.svg` uses the<br>
portrait's own character ramp: `:` `+` `#` `@`, quiet to loud.

Pipeline and portrait technique adapted from the [ASCII Portrait README<br>
Guide](https://burly-handstand-0dc.notion.site/ASCII-Portrait-README-Guide-3a3e3f86338481f0b545ec8120bbf604).
