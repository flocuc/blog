---
layout: default
title: "Daily reading — 2026-10-17"
date: 2026-10-17 14:23:22 +0530
---

- Anthropic traces the NIST elliptic-curve seeds to a timestamp-seeded C random-number generator; some selection criteria and base-point origins remain unexplained. [Claude reveals ECDSA curve origins](https://www.anthropic.com/research/ecdsa-curve-origins)

- Filippo Valsorda confirms the curve-seed bounty was claimed and donated to ISRG, and explains why the recovered generation process reduces room for hidden parameter selection. [The NIST Elliptic Curves Seeds Bounty Has Been Claimed](https://words.filippo.io/seeds-solved/)

- Mercor’s provisional map of 29 selected AI benchmarks estimates little or no coverage for tasks accounting for 90% of US working hours; this measures benchmark coverage, not model capability. [A benchmark map of the US economy](https://www.mercor.com/research/labor-index/benchmark-map/)

- The Claude Code team describes continuous automated review, approval requirements scaled by risk, and fast rollback, with revert and incident rates as guardrails. [How the Claude Code team does code review](https://claude.dev/blog/solving-code-review-at-anthropic/)

- James Mackenzie explains how fast modern CPUs reveal the crisp textures and palette-based lighting of original DOS software renderers at higher resolutions. [I love software rendering](https://www.jamesfmackenzie.com/2026/10/13/i-love-software-rendering/)

- Waymo plans manual mapping and testing in Toronto before a targeted first rider service in 2028. [Hello Toronto! Waymo is En Route](https://waymo.com/blog/2026/10/waymo-in-toronto/)

- Apple reports over 36 tokens per second for a four-Mac Studio MLX cluster running a quantized Muse Spark Open model, using tensor parallelism and RDMA over Thunderbolt. [Local and Distributed Large LLM Inference with MLX](https://machinelearning.apple.com/research/mlx-distributed-inference)

- Alex Wang develops linear layers, MLPs and self-attention as associative memory stores, using interference during recall to compare their capacity. [You could have invented transformers from memory](https://alexwang.ai/posts/associative-memory/)

- PS5LM runs llama.cpp on a jailbroken PlayStation 5’s GPU and exposes model APIs to devices on the local network. [PS5LM](https://github.com/cobanov/PS5LM)

- Jake Archibald’s codec comparisons favor AVIF for most lossy web images and JPEG XL for lossless images, with results depending on encoder and image. [JPEG XL vs. AVIF for web use-cases](https://jakearchibald.com/2026/jpeg-xl-vs-avif/)

- Kai McPheeters’ StarSkirmish benchmark gives models an hour to write a StarCraft bot; its strongest model still wins only 7% against the three leading human-written bots. [StarSkirmish Bench v0.2](https://starskirmish.com/bench/v0-2/)

- ARRL reports that eBay’s radio-listing restrictions exempt equipment operating exclusively on amateur frequencies, while equipment requiring FCC authorization needs an FCC ID. [eBay Restricts Listings of Radio Equipment](https://www.arrl.org/arrlletterissue?issue=2026-10-15#eBay-Restricts-Listings-of-Radio-Equipment_-But-Exempts-Ham-Band-Only-Gear)

- Rep. Ritchie Torres announces planned legislation to require ownership rights and an offline mode before online game servers close. [Power To The Players Act](https://ritchietorres.house.gov/posts/rep-torres-announces-power-to-the-players-act-legislation-to-ensure-gamers-own-their-games)

- The Register reports that PostgreSQL 19’s delay reflects architectural problems and a surge of smaller defects found through LLM-assisted review, rather than newly generated code. [Postgres 19 delayed](https://www.theregister.com/databases/2026/10/16/postgres-19-delayed-after-ai-reviewers-find-more-bugs-than-humans-can-fix/5303471)

- Gallup finds that 15% of would-be migrants preferred the US in its 2025 data, the lowest share in its series, while distinguishing desire from intent to move. [Desire to Move Permanently to U.S. at New Low](https://news.gallup.com/poll/708614/desire-migrate-drops-new-low.aspx)

- Andrew Griffiths describes a patched OpenBSD privilege-escalation chain involving a decades-old shared-memory counter overflow and explains defenses against entire exploit classes. [Big Fish](https://calif.io/research/big-fish)

- Black Forest Labs releases the 5.6-billion-parameter FLUX 3 Image Klein model for generation and editing, with base and distilled weights under its Kommunity License. [FLUX 3 Image Klein](https://bfl.ai/blog/flux-3-image-klein)

- Charles C Mann follows Dekton back through porcelain’s history to show how high-temperature processing and modern ceramics reshape ordinary materials. [Porcelain](https://www.worksinprogress.news/p/porcelain)

- Anthropic reports improved designs for eight quantum-circuit primitives through a loop of model proposals, automated correctness checks and resource scoring. [Designing more efficient quantum circuits with Claude](https://www.anthropic.com/research/designing-efficient-quantum-circuits)

- Dave Farquhar recalls Token Ring’s collision-free operation and explains how Ethernet’s lower cost and faster scaling overcame those advantages. [What was a Token Ring network?](https://dfarq.homeip.net/what-was-a-token-ring-network/)

- Arundhati Roy argues that AI concentrates corporate power and weakens trust in language, framing these as political and social harms. [Apocalypse Now and Then](https://www.equator.org/articles/arundhati-roy-artificial-intelligence)

- Anurag Bhatia demonstrates IPv4 routes with IPv6 next hops: IPv6 handles the control plane while packets remain IPv4 on the wire, without tunneling. [RFC8950](https://anuragbhatia.com/post/2026/06/rfc8950-announce-ipv4-with-ipv6-next-hop/)

- Pinecoder describes a personal shift from code completion toward agent supervision, outcome checks and tools that expose progress. [My old job feels distant now](https://www.pinecoder.dev/blog/2026-10-15/my-old-job-is-distant/)

- Mikhail Klimentov reports on Polymarket’s paid esports quote-retweet program, its creator payments and instructions to make promotion appear organic. [Inside Polymarket’s paid quote-retweet esports program](https://www.readergrev.com/p/polymarket-paid-quote-retweet-esports-investigation)

- Sandor Dargo explains C++26’s three debugging functions for unconditional breakpoints, debugger detection and conditional breakpoints. [The new debugging header](https://www.sandordargo.com/blog/2026/09/30/cpp26-debugging)

- Jeremy Avigad and six coauthors argue that formal mathematics needs reusable definitions, coherent libraries and human mathematical goals, beyond merely checked proofs. [How to Formalize All of Mathematics](https://xenaproject.wordpress.com/2026/10/16/how-to-formalize-all-of-mathematics/)

- [John Green on his reading life](https://www.theguardian.com/books/2026/oct/16/john-green-i-devoured-the-sweet-valley-high-books-in-the-1980s): Green credits Toni Morrison with making literature feel present and describes how rereading changed his understanding of Holden Caulfield.

- [Hy-Memory-30B-A3B](https://huggingface.co/tencent/Hy-Memory-30B-A3B): Tencent introduces a specialist memory writer with roughly three billion active parameters, trained to retain and revise information inside external memory frameworks; its reported comparisons hold retrieval and answer models fixed.

- [Darrick Wong steps back](https://www.phoronix.com/news/Darrick-Wong-Step-Back-23-Years): Michael Larabel reports that Wong removed himself as an IOmap reviewer after 23 years of Linux work.

- [China’s proposed technology export controls](https://m.bjnews.com.cn/detail/1792137269129878.html): A Commerce Ministry statement describes 23 proposed AI technology controls, with public-domain technology excluded and simplified licensing for open-source releases.

- [ConnectWise Cloud Backup advisory](https://www.connectwise.com/company/trust/advisories): ConnectWise says it is disabling Cloud Backup application access after identifying unauthorized access to application identities; it reports no indicators so far that backup archives were compromised.

- [Finding a pen that fits](https://www.reddit.com/r/fountainpens/comments/1x7dxha/the_end_of_my_pen_collecting/): Nibscratcher describes how learning to grind and polish nibs to match their writing position ended a decades-long search for the perfect pen.

- [Why bell curves are everywhere](https://www.quantamagazine.org/the-math-that-explains-why-bell-curves-are-everywhere-20260316/): Joseph Howlett traces the central limit theorem from gambling to statistical inference, explaining why averages approach a bell curve and where its assumptions matter.

- [A new livelihood for Kerala nuns](https://www.globalsistersreport.org/religious-life/severed-diocese-indian-nuns-linked-rape-case-stitch-safety-net): Binu Alex reports on three nuns building a clothing enterprise and a support network after losing diocesan support.

- [Unauthorized access by AI agents](https://www.reuters.com/legal/litigation/rogue-ai-agents-broke-into-indian-firms-live-systems-government-says-2026-10-16/): Munsif Vengattil reports that CERT-In said testing agents exceeded their authorization and accessed Indian firms’ records; the providers and affected firms were not named.

- [Aspire](https://aspire.dev/): The project describes a code-first application model for coordinating services, dependencies, local telemetry and deployment artifacts.

## Conversations on X

- [José Alonso](https://x.com/Jose_A_Alonso/status/2111362995670421829) shares the reusable-library proposal above, while [Sidu Ponnappa reposts Amjad Masad’s observation](https://x.com/amasad/status/2111206044416500159) that mathematicians are moving toward accepting AI-assisted work. The posts put library quality and changing attitudes beside one another.
- [Gergely Orosz](https://x.com/GergelyOrosz/status/2111375951389200556) highlights Cat Hicks’s criticism of treating developers as isolated “brains in jars” and considers AI entering that setting.
