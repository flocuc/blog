---
layout: default
title: "Daily reading — 2026-11-01"
date: 2026-11-06 13:57:00 +0530
permalink: /2026/11/01/daily-reading/
---

- [HackerTube](https://karpathy.bearblog.dev/hacker-tube/): Andrej Karpathy builds a video interface around Hacker News recommendations, replacing uploaded thumbnails with mid-video frames and keeping preference state locally.
- [Linux’s TCP use-after-free](https://atlasum.net/blog/cve-2026-98432-linux-ipv4-tcp-uaf): Atlas Security explains an IPv4 handshake flaw and the gap between upstream fixes and distribution kernels, distinguishing temporary mitigations from an installed, running fix.
- [A Scribd incident notice](https://news.ycombinator.com/item?id=50312756): An HN author shares a notice describing possible exposure of email addresses and limited payment-related information, with no evidence of misuse stated in the notice.
- [Molly’s update gap](https://piefed.world/post/1503394): A PieFed author warns that the Signal fork has fallen behind upstream security fixes, highlighting the maintenance burden of security-focused forks.
- [Digital minimalism](https://vitalik.eth.limo/general/2026/10/31/digital_minimalism.html): Vitalik Buterin describes reducing algorithmic feeds and mobile connectivity, pairing offline knowledge with local tools while acknowledging practical inconveniences.
- [A fixed ChatGPT account-takeover chain](https://www.parameter.ai/labs/we-found-a-gap-at-openai): Parameter describes how trusted cross-frame messages defeated otherwise isolated previews, reporting that OpenAI fixed the issue on October 26.
- [VOLTA’s AI-assisted victim profiling](https://blog.talosintelligence.com/appraisal-by-ai-model-driven-victim-prioritization-in-the-volta-infostealer/): Ryan Fetterman reports that an infostealer adds model-generated assessments after collecting data, shifting the operator’s analytical work to an optional AI stage.
- [Research automation restrictions](https://twitter.com/jiahaoshao1/status/2116475922190922088): Jiahao Shao says Claude blocked model-training research automation despite his rollouts coming from an open model rather than Claude distillation.
- [Greens reconsider nuclear power](https://www.theguardian.com/politics/2026/oct/05/green-party-nuclear-power-policy): Matthew Pearce reports that England and Wales’s Green party replaces blanket opposition with case-by-case assessment, while retaining renewables as its priority.
- [Switch lowering in GCC](https://xoranth.net/gcc-switch/): Xoranth traces how case density, shared targets and branch probabilities lead GCC to choose bitsets, jump tables or comparison trees.
- [Prospero](https://nullprogram.com/blog/2026/10/31/): Chris Wellons presents a lean C++ coding harness with passive rendering, operation deadlines and process-tree cleanup; model access is supplied separately.
- [Rediscovering miracle wheat](https://www.smithsonianmag.com/science-nature/italian-farmer-found-unknown-seeds-attic-with-nothing-lose-planted-them-result-biblical-180989644/): Lina Zeldovich follows Claudio Grossi’s revival of heritage poulard wheat, including its resilience and the lodging risk of its tall stems.
- [GPT-5.6 Sol plays Factorio](https://ryanmadden.net/gpt-56-beats-factorio/): Ryan Madden reports a completed peaceful run in 13.5 game hours, with late production failures compensated by repeated supply ferrying.
- [Memory latency and GROUP BY](https://pivotlake.io/blog/its-the-memory-latency-stupid/): Maor Kern demonstrates how radix partitioning makes aggregation faster by improving cache locality, despite performing more CPU operations.
- [French data-flow tax amendment](https://www.assemblee-nationale.fr/dyn/17/comptes-rendus/seance/session-ordinaire-de-2026-2027/premiere-seance-du-vendredi-30-octobre-2026): The Assembly’s record shows amendment 1358 passing 11–10; ministers opposed the proposal over measurement and its burden on smaller content providers.
- [Disputed Books3 testimony](https://torrentfreak.com/ex-meta-researcher-torrented-pirated-books-dataset-deleted-it-due-to-all-this-litigation/): Ernesto Van der Sar reports conflicting interpretations by rightsholders and Meta of a former researcher’s torrent download and later deletion of the dataset.
- [Team-solve workflow](https://github.com/guregodevo/memdoor/tree/main/examples/workflows/team-solve): Memdoor’s author reports 49 successes in 50 runs across ten coding problems, while documenting possible training contamination and cases where a manager replaced correct code.
- [The duty of a scholar](https://www.daemonology.net/blog/2026-10-31-The-Duty-of-a-Scholar.html): Colin Percival argues that knowledge carries a duty to find the people who need it, while respecting their freedom to decline or act on it.
- [Voyager’s light-day milestone](https://science.nasa.gov/mission/voyager/voyager-1/voyager-1-what-is-a-light-day/): NASA expects Voyager 1 to reach one light-day from Earth on November 18, nearly fifty years after launch.
- [Protesting delivery robots](https://www.cnn.com/2026/10/31/us/philadelphia-woman-delivery-robots-cec): Zoe Sottile reports Carolyn Marvin’s arrest after blocking a Philadelphia delivery robot, alongside her objections to machines occupying public sidewalks.
- [Campaign account suspension](https://newrepublic.com/post/217281/meta-suspend-democratic-candidate-angie-nixon-instagram-account): Malcolm Ferguson reports that Angie Nixon’s Latino-outreach Instagram account was suspended during a rally and restored about an hour later, without a reported explanation.
- [ParticleDB under Jepsen testing](https://jepsen.io/analyses/particledb-1.1.4): Kyle Kingsbury reports severe correctness and data-loss bugs in tested single-node builds; Orkes says a later release fixes them, which Jepsen has not verified.
- [Vocabulary coverage versus whole lines](https://learnfromx.com/research/anime-word-coverage-vs-lines-understood): LearnFromX measures a wide gap between familiar word occurrences and subtitle lines containing only familiar words, while stressing that this proxy does not measure actual comprehension.
- [Flock searches after an abuse case](https://www.wkyc.com/article/news/investigations/flock-camera-searches-fall-95-percent-highland-heights-dispatcher-misconduct-caught/95-94b18f33-60e2-4bc7-a00f-d71d1e1fdd5e): Silas Tsang and Peter Fleischer report that Highland Heights searches fell over 95% after a dispatcher’s personal tracking was exposed and monthly audits were introduced.

- Matt Gravelling reports that Gruffalo illustrator Axel Scheffler is considering legal action in Germany over AI reproductions of his characters; no target company or filed case is announced. [Report](https://www.bbc.com/news/articles/cj04032rp5wro)
- Arjun Ingole’s hop stages a Linux installer on an internal FAT32 partition and adds a one-time UEFI boot entry, allowing supported Windows PCs to start a dual-boot installation without a USB stick. [Repository](https://github.com/Arjun-Ingole/hop)
- Hacktron reports a Savannah exploit chain from email-address shell injection to root access; the FSF says it patched the flaws and found no evidence that project data, credentials or the software supply chain were compromised. [Investigation](https://www.hacktron.ai/blog/hacking-gnu-savannah)
- Betelgeuse pages MoE experts between NVMe, RAM and VRAM; its documentation limits the roughly 22-token-per-second result to historical repeated-workload runs on one RTX 3060 setup and labels the project experimental. [Repository](https://github.com/Betelgeuse-AI/Betelgeuse)

- [loccount](https://gitlab.com/esr/loccount) counts source and logical lines, identifies languages and exports structured reports; Eric S. Raymond’s 2.26 release lists support for 772 languages.
- [The Times of Israel](https://www.timesofisrael.com/liveblog_entry/veteran-mk-tibi-pledges-arab-parties-support-from-outside-for-a-potential-eisenkot-led-government-i-dont-want-a-ministry-we-want-change/) reports that Ahmad Tibi offered the Joint List’s support for an Eisenkot-led government from outside the coalition, without seeking a ministry.

## Conversations on X

- [Dax](https://x.com/thdxr/status/2116696790757986482) argues that solving a problem he has himself makes it easier to build a good product, provided others can use it too. His quoted counterpoint from Jon Yongfook is that developers who can generate their own replacements make a difficult customer base.
- [Eric S. Raymond](https://x.com/esrtweet/status/2116670263991632185) predicts that tighter AI regulation would protect cloud providers and constrain open models; this is his forecast of the political incentives.
