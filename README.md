# Welcome

My work involves making complex systems understandable 
by making their structure, assumptions, and tradeoffs explicit:
whether that's how a language model predicts the next token, 
how an agent discovers what tools it has, or 
how a community weighs competing options in high-stakes decisions.

I like taking systems that are opaque, implicit, or fragmented
and making them inspectable, structured, and decision-capable.

## Structural Explainability

- [structural-explainability](https://github.com/structural-explainability) - designing information structures
  that remain reliable over time, even when interpretations differ.
  Explores ideas applicable to science, policy, law, civic infrastructure, digital twins, and AI explainability.

## Civic Interconnect

Structured tools for making competing values and policy assumptions 
visible in high-stakes civic decisions. 
Multidimensional evaluation projects include:

### ⭐Interactive Explorer: Data Centers

- [**Interactive Explorer**](https://civic-interconnect.github.io/decision_explorer_data_centers/explorer/)
- [Repository](https://github.com/civic-interconnect/decision_explorer_data_centers)

### ⭐Interactive Explorer: Age Verification

- [**Interactive Explorer**](https://civic-interconnect.github.io/explorer-age-verification/explorer/)
- [Repository](https://github.com/civic-interconnect/explorer-age-verification)

### Multidimensional Evaluation Engine

Explorers are based on the Multidimensional Evaluation Engine:
A domain-neutral engine for multidimensional evaluation under explicit policy assumptions.

- [multidimensional-evaluation-engine](https://github.com/civic-interconnect/multidimensional-evaluation-engine)
- [On PyPi](https://pypi.org/project/multidimensional-evaluation-engine/)

## Selected Curriculum, Software, and Course-Architecture Work

I design and maintain durable, project-centered curriculum ecosystems for applied computing, 
data analytics, streaming data, continuous intelligence, web mining, natural language processing, 
and professional Python workflows. 
These courses use repeatable module patterns, modern Python tooling, GitHub-based project practice, 
and student-facing repositories designed to encourage reusable professional workflows, 
support independent progress, and build transferable technical skills.

## Natural Language Processing and LLM/GPT Exploration

Developed hands-on examples showing how GPT-style language models repeatedly predict the next token 
using training text, context windows, and learned patterns. 
Materials include an interactive text-prediction app and progressive examples 
comparing pre-trained models with different context-window sizes and 
different training-text structures. 
Used to explore how context, training data, and model design shape 
next-token predictions in language-model behavior.

Artifacts include:

- Interactive GPT-style next-token prediction app and source repo
- Progressive examples using 0, 1, 2, and 3-word context windows
- Comparisons using neutral and structured training text
- `toy-gpt` exploration materials
- [App (Text Prediction)](https://toy-gpt.github.io/toy-gpt-chat/) - interactive next-token prediction in GPT-style language models
- [App (Text Prediction) Source Repo](https://github.com/toy-gpt/toy-gpt-chat)
- [Introduction and Pre-Trained Models](https://github.com/toy-gpt/) - progressive example training repos

## Adaptive Interfaces

Developed tools and conventions that help AI agents understand, navigate, and 
work reliably with external systems. 
The work uses explicit project conventions, including SKILL.md-based guidance, 
to support agent conformance, tool discovery, and project onboarding.

Artifacts include:

- [Adaptive Conformance Specification (ACS)](https://github.com/adaptive-interfaces/adaptive-conformance-specification) -  behavioral protocol for observing, inferring, and conforming before generating artifacts
- [Adaptive Tool Discovery (ATD)](https://github.com/adaptive-interfaces/adaptive-tool-discovery) - capability mapping for external tool sets
- [Adaptive Onboarding (AO)](https://github.com/adaptive-interfaces/adaptive-onboarding) - context-building for team/project conventions, ownership, and norms
- [Example repo](https://github.com/denisecase/.adaptive](https://github.com/denisecase/.adaptive)

## Professional Python for Analytics (New 2026)

Created standards-based tooling and guides for professional Python analytics workflows, 
using uv, ruff, Zensical, GitHub repositories, and modern project conventions.

- [⭐applied-computing-foundations](https://denisecase.github.io/applied-computing-foundations/) - repos, file systems, terminals, and navigation basics
- [⭐GUIDE: pro-analytics-02](https://denisecase.github.io/pro-analytics-02/) - guide to professional analytics using `uv` and Python
- [⭐datafun-toolkit](https://github.com/denisecase/datafun-toolkit) - [PyPi package](https://pypi.org/project/datafun-toolkit/) - privacy-aware logging and diagnostics
- [⭐datafun-streaming](https://github.com/denisecase/datafun-streaming) - [PyPi package](https://pypi.org/project/datafun-streaming/) - streaming data analytics utilities
 
## Syllabus Generator

Developed a syllabus-generation workflow that builds syllabi from structured TOML data and a 
reusable template, supporting consistency, maintainability, and efficient updates.

- [Syllabus Generator](https://github.com/denisecase/syllabus-generator) - build from TOML and a template

## Data Analytics Fundamentals

Designed and maintained a seven-module curriculum for professional Python fundamentals in data analytics.
The curriculum progresses from project setup and Python foundations through automation, 
structured data processing, notebooks, SQL, applied analytics, and regression.

- [IntroToPython](https://github.com/denisecase/IntroToPython) - professional project setup for the [textbook examples](https://github.com/pdeitel/IntroToPython)
- [datafun-01-foundations](https://github.com/denisecase/datafun-01-foundations) - professional Python foundations
- [datafun-02-automation](https://github.com/denisecase/datafun-02-automation) - automation with repetition, ranges, list comprehensions, delays
- [datafun-03-analytics](https://github.com/denisecase/datafun-03-analytics) - read, process, write text and structured data
- [datafun-04-notebooks](https://github.com/denisecase/datafun-04-notebooks) - explore/present insights using Python and Markdown in a Jupyter notebook
- [datafun-05-sql](https://github.com/denisecase/datafun-05-sql) - Python and SQL
- [datafun-06-applied](https://github.com/denisecase/datafun-06-applied) - applied analytics project
- [datafun-07-regression](https://github.com/denisecase/datafun-07-regression) - linear regression and prediction

## Data Analytics Fundamentals: Automation and Maintenance

- [datafun-00-admin](https://github.com/denisecase/datafun-00-admin) - maintaining and updating course repos

## Streaming Data

Designed and maintained a seven-module curriculum for professional streaming data pipelines in Python.
The curriculum moves from simulated streams to Kafka producers and consumers, 
derived fields, validation, visualization, storage, and applied streaming scenarios.

- [streaming-01-foundations](https://github.com/denisecase/streaming-01-foundations) - Python generator and simulated data streams
- [streaming-02-kafka](https://github.com/denisecase/streaming-02-kafka) - Kafka producers and consumers
- [streaming-03-analytics](https://github.com/denisecase/streaming-03-analytics) - adding derived fields and validation
- [streaming-04-visualization](https://github.com/denisecase/streaming-04-visualization) - live charts and real-time updates
- [streaming-05-storage](https://github.com/denisecase/streaming-05-storage) - streaming data and databases
- [streaming-06-scenarios](https://github.com/denisecase/streaming-06-scenarios) - streaming scenarios
- [kafka-producer-earthquake](https://github.com/denisecase/kafka-producer-earthquake) - Kafka producer for streaming earthquake data from USGS API
- [dc-mailer](https://github.com/denisecase/dc-mailer)
- [dc-texter](https://github.com/denisecase/dc-texter)

## Streaming Data: Automation and Maintenance

- [streaming-00-admin](https://github.com/denisecase/streaming-00-admin) - maintaining and updating course repos

## Continuous Intelligence

Designed a seven-module curriculum for building real-time anomaly detection, signal monitoring, and drift-detection systems in Python.
The curriculum emphasizes applied monitoring workflows, signal design, rolling analysis, drift detection, 
and continuous intelligence systems.

- [cintel-01-getting-started](https://github.com/denisecase/cintel-01-getting-started)
- [cintel-02-static-anomalies](https://github.com/denisecase/cintel-02-static-anomalies)
- [cintel-03-signal-design](https://github.com/denisecase/cintel-03-signal-design)
- [cintel-04-rolling-monitoring](https://github.com/denisecase/cintel-04-rolling-monitoring)
- [cintel-05-drift-detection](https://github.com/denisecase/cintel-05-drift-detection)
- [cintel-06-continuous-intelligence](https://github.com/denisecase/cintel-06-continuous-intelligence)
- [cintel-stock-response](https://github.com/denisecase/cintel-stock-response)
- [fetch-data-weather](https://github.com/denisecase/fetch-data-weather)

## Web Mining and Applied Natural Language Processing (NLP)

Designed and maintained a seven-module curriculum covering text preprocessing, text exploration, 
API-based data collection, web document acquisition, and NLP pipelines.

- [nlp-01-getting-started](https://github.com/denisecase/nlp-01-getting-started)
- [nlp-02-text-preprocessing](https://github.com/denisecase/nlp-02-text-preprocessing)
- [nlp-03-text-exploration](https://github.com/denisecase/nlp-03-text-exploration)
- [nlp-04-api-text-data](https://github.com/denisecase/nlp-04-api-text-data)
- [nlp-05-web-documents](https://github.com/denisecase/nlp-05-web-documents)
- [nlp-06-nlp-pipeline](https://github.com/denisecase/nlp-06-nlp-pipeline)
- [toy-gpt exploration](https://github.com/toy-gpt)

![Happy Winter](./images/2026-02-23-moon-halo.png)

## Diversify

- [Quad9 DNS Resolver](https://quad9.net/) - free service
  - Firefox / Settings / Privacy & Security: DNS over HTTPS, enable Max and set to <https://dns.quad9.net/dns-query> OR add Mullvad VPN and set to Default.
  - Chrome / Settings / Privacy & Security / Security / Use secure DNS: toggle on, select Custom, enter <https://dns.quad9.net/dns-query>
  - Android / Settings / Network & Internet / Private DNS: Set Private DNS provider hostname to <dns.quad9.net> OR add Mullvad VPN and set to Automatic.
  - Starlink App / Settings / Router tab / Custom DNS: Toggle on, enter Primary: 9.9.9.9 and Secondary: 149.112.112.112 (allow 10 min to apply)
  - Windows / Settings / Network & internet / WiFi / Choose the network name / DNS server assignment: click Edit / Toggle on IPV4 / Preferred DNS: 9.9.9.9 DNS over HTTPS: On (automatic template) / Alternate DNS: 149.112.112.112 DNS over HTTPS: On (automatic template) / click Save.
  - Verify: <https://on.quad9.net>
- [Proton Mail Plus](https://proton.me/mail) - email provider, $48/yr
- [Proton Pass](https://proton.me/pass) - password storage (if using Proton Mail)
- [BitWarden](https://bitwarden.com/) - password storage
- [Firefox Browser](https://www.firefox.com/) with
  - [Containers](https://addons.mozilla.org/en-US/firefox/addon/multi-account-containers/)
  - [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)
  - Settings / Privacy & Security: Standard or Strict Tracking Protection
  - Settings / Privacy & Security: UNCHECK Ask to save passwords
  - Settings / Privacy & Security: DNS over HTTPS, enable Max and set to <https://dns.quad9.net/dns-query>
- [FUTO Keyboard](https://keyboard.futo.org/) - mobile keyboard with swipe and voice that sends nothing (still in alpha)
- [Mullvad VPN](https://mullvad.net/) - VPN for 5 devices, $78/yr, Windows 11, Mac, Android
  - Verify at <https://mullvad.net/en/check>
  - Settings / Local network sharing / Allow LAN traffic ON for WiFi Printer (or use split tunneling)
 
## Sign-in Sheet Builder

- [signin-sheet-builder](https://github.com/denisecase/signin-sheet-builder) - when you have too many columns to fit on a landscape page and you want 2 rows per member

## Generate QR Code (web app)

- [Web App](https://denisecase.github.io/qr-gen/) - generate a QR code from a web link or text
- [App Repo](https://github.com/denisecase/qr-gen)

## Templates

- [templates](https://github.com/denisecase/templates) - favorite CI/CD GitHub actions, config files, MkDocs, etc.
- [chrome_new_tab_ext](https://github.com/denisecase/chrome_new_tab_ext)

## Databases for Analytics

- [databases-for-analytics](https://github.com/denisecase/databases-for-analytics)

## Applied Machine Learning

- [applied-ml-template](https://github.com/denisecase/applied-ml-template) - copy this to your GH and replace template with yourname
- [confusion-matrix-explorer](https://github.com/denisecase/confusion-matrix-explorer) - PyShiny interactive app repo - try the [app here](https://denisecase.github.io/confusion-matrix-explorer/app/).
- [ml-04](https://github.com/denisecase/ml-04) - classification analysis
- [ml-07](https://github.com/denisecase/ml-07) - regression analysis

## Professional Python for Analytics (Earlier Version 01)

- [datakit-lite](https://github.com/denisecase/datakit-lite)

Uses `pip` and `venv` with `requirements.txt`:
- [pro-analytics-01](https://github.com/denisecase/pro-analytics-01)
- [pro-analytics-01-audio-guides](https://github.com/denisecase/pro-analytics-01-audio-guides) - repo used to generate podcasts with AI (crazy!)
- [Listen](https://denisecase.github.io/pro-analytics-01-audio-guides/) <-- try the podcasts here

## Applied Guides: Getting Started with Computer Basics

- [applied-computer-organization](https://github.com/denisecase/applied-computer-organization/)

## Fun, Free Games

![rock games icon](./images/RockGamesIcon.png)
- [RockSwap](https://denisecase.github.io/rockswap/) - match-3 game
  - [(repo)](https://github.com/denisecase/rockswap) - source code
- [RockSwap-Vivid](https://denisecase.github.io/rockswap-vivid/) - match-3 game (red-green colorblind safe)
  - [(repo)](https://github.com/denisecase/rockswap-vivid) - source code
- [RockFit](https://denisecase.github.io/rockfit/) - falling blocks game
  - [(repo)](https://github.com/denisecase/rockfit) - source code
 
## Civic

- [Life Expectancy at Birth (1960–2022)](
https://mybinder.org/v2/gh/denisecase/progress-atlas/HEAD?urlpath=voila%2Frender%2Fnotebooks%2Flife_expectancy_compare.ipynb) - interactive chart to compare life expectancy at birth by country, region, or economic classification.
- [Life Expectancy By Location (Bar Chart Race)](https://youtu.be/Kn0M-vOGjjI) - YouTube video of the top 30 from 1960-2022
   - [Progress Atlas: Source](https://github.com/denisecase/progress-atlas)
- [Minnesota GIS: Viewer](https://mybinder.org/v2/gh/denisecase/gis-mn-civic/HEAD?urlpath=voila/render/main.ipynb)
  - [Minnesota GIS: Source](https://github.com/denisecase/gis-mn-civic)
- [Civic Interconnect (organization](https://github.com/civic-interconnect)

## Built with Zig (Super Fast, Super Fun, Easy Executables)

- ☆[Zig Bill Utils](https://github.com/denisecase/zig-bill-utils) - high-performance toolkit for analyzing U.S. legislative bills.![United States](https://raw.githubusercontent.com/stevenrskelton/flag-icon/master/png/16/country-4x3/us.png "United States")
- ☆[Py Bill Utils](https://github.com/denisecase/py-bill-utils) - Python project for analyzing U.S. legislative bills.![United States](https://raw.githubusercontent.com/stevenrskelton/flag-icon/master/png/16/country-4x3/us.png "United States") - uses [Zig Bill Utils](https://github.com/denisecase/zig-bill-utils)

## Just for Fun

- [Zipline Estimator Visualizer](https://denisecase.github.io/zipline-estimator/)
- [Zipline Estimator: Source on GitHub](https://github.com/denisecase/zipline-estimator)

## Interesting and/or Fun Tech

- [Google NotebookLM](https://notebooklm.google.com/) - AI-generated summaries, Q&A, and podcasts from your own documents and sources.
- [Meta Quest Virtual Reality](https://www.meta.com/quest/) - immersive games, learning, productivity, and creativity in mixed reality.
- [Google Apps Script](https://developers.google.com/apps-script) - automate workflows in Google Drive, Docs, Sheets, Gmail, and more using JavaScript-like scripting.
- [Microsoft Quantum Simulator](https://quantum.microsoft.com/)  - Try quantum computing in your browser—no special hardware required.
- [Learn with Quantum Katas](https://quantum.microsoft.com/en-us/tools/quantum-katas) - interactive notebook tutorials for quantum logic and computation.
- [Viola the Bird](https://artsandculture.google.com/experiment/viola-the-bird/nAEJVwNkp-FnrQ?hl=en) - interactive experiment blending machine learning with cello-inspired play.
- [BirdNET – Identify Bird Sounds with ML](https://birdnet.cornell.edu/) - Upload audio or use field device to identify birds by sound with bioacoustics AI.
- [GitHub Copilot Workspace](https://githubnext.com/projects/copilot-workspace/) - AI-powered IDE that understands your repo, suggests tasks, writes code, and walks through implementation plans.
- [GitHub Copilot Voice](https://githubnext.com/projects/copilot-voice/) - use your voice to code (without spelling things out)
- [More GitHub Next Projects](https://githubnext.com/) - cutting-edge developer tools being prototyped by GitHub.

## Playing with Virtual Reality

-  🆕[Visit VR Forest](https://denisecase.github.io/vr-forest/)
-  🆕[See the code](https://github.com/denisecase/vr-forest)


## Example of Building an LLM AI System to Help with Pro-Analytics-01

- [pro-analytics-ai](https://github.com/denisecase/pro-analytics-ai) — illustrates how LLMs like ChatGPT work by creating an AI assistant trained on [pro-analytics-01](https://github.com/denisecase/pro-analytics-01). It uses APIs (OpenAI/OpenRouter) to process user prompts and generate natural language responses, but all retrieval and context selection is performed locally based on the source repository text.
- The AI assistant runs locally on a 2 TB SSD machine with 12/24 cores, using API calls (via a free OpenRouter API key).
- The frontend is lightweight, but the backend uses a local retrieval pipeline (ChromaDB + sentence-transformers) that depends on large Python ML libraries, making it too heavy for serverless platforms like AWS Lambda and significant even for AWS EC2.
- Even when calling external APIs (and not hosting full LLM models), generating embeddings and performing document retrieval requires a significant machine learning environment.
- When we **build a brain** by indexing our own documents, the storage, memory, and processing requirements expand dramatically.

Early work:

- 2020 May Research Paper introducing GPT-3: ["Language Models are Few-Shot Learners"](https://arxiv.org/abs/2005.14165)
- 2022 Nov OpenAI ChatGPT "research preview. [Current link](https://openai.com/chatgpt/overview/)
- 2023 Nov: OpenAI [DevDay](https://openai.com/devday/2024/) - first developer conference (GPT-4 Turbo, and more).
- Conferences:
  - [NeurIPS](https://neurips.cc/) - Neural Information Processing Systems
  - [ICML](https://icml.cc/) - International Conference on Machine Learning

##  A public-health data microservice deployed to GKE Autopilot using FastAPI, Docker, and Kubernetes

- 🆕[k8s-api-mosquito](https://github.com/denisecase/k8s-api-mosquito)

## Interactive Dashboard (In Progress)

- [open-climate-disaster-dashboard](https://github.com/denisecase/open-climate-disaster-dashboard)

## MandArt Web (powered by wasm)

- [App mandart-web](https://denisecase.github.io/mandart-web/) 
- [Repo mandart-web](https://github.com/denisecase/mandart-web/)

<div align="center">
  <img src="https://github.com/denisecase/mandart-web/blob/main/examples/bright.jpg?raw=true" width="200" height="200">
  <img src="https://github.com/denisecase/mandart-web/blob/main/examples/navy.jpg?raw=true" width="200" height="200">
</div>

## Mandart Engine (Rust)

- [test page](https://denisecase.github.io/mandart-engine-rust/)
- [mandart-engine-rust](https://github.com/denisecase/mandart-engine-rust/)
- Comparing [input](https://github.com/denisecase/mandart-engine-rust/tree/main/input) to [output](https://github.com/denisecase/mandart-engine-rust/tree/main/output)
- Example [input Frame25](https://github.com/denisecase/mandart-engine-rust/blob/main/output/Frame25.png) and [output Frame25](https://github.com/denisecase/mandart-engine-rust/blob/51267a422943c80b571ed16095b2644963d1a143/output/Frame25.png)
<div align="center">
  <img src="https://github.com/denisecase/MandArt-Discoveries/blob/main/brucehjohnson/frame_pix/Frame25.png?raw=true" width="200" height="200">
  <img src="https://github.com/denisecase/mandart-engine-rust/blob/51267a422943c80b571ed16095b2644963d1a143/output/Frame25.png?raw=true" width="200" height="200">
</div>
 
## Smart Sales 

- [smart-sales-analysis-goals](https://github.com/denisecase/smart-sales-analysis-goals)
- [smart-sales-raw-data](https://github.com/denisecase/smart-sales-raw-data)
- [smart-sales-example](https://github.com/denisecase/smart-sales-example)
- [smart-sales-starter-files](https://github.com/denisecase/smart-sales-starter-files)
- [smart-sales-docs](https://github.com/denisecase/smart-sales-docs)
- [smart-sales-olap](https://github.com/denisecase/smart-sales-olap)
- [smart-sales-spark](https://github.com/denisecase/smart-sales-spark)
- [smart-sales-duckdb-sql](https://github.com/denisecase/smart-sales-duckdb-sql)
- [smart-sales-duckdb-sql-python](https://github.com/denisecase/smart-sales-duckdb-sql-python)

## World Diabetes Day - November 14

[World Diabetes Day (WDD)](https://worlddiabetesday.org/) is the world’s largest diabetes awareness campaign reaching a global audience of over 1 billion people in over 160 countries.
It is marked every year on 14 November, the birthday of Sir Frederick Banting, who co-discovered insulin along with Charles Best in 1922.

WDD was created in 1991 by International Diabetes Federation (IDF) and the World Health Organization and became an official United Nations Day in 2006 with the passage of United Nations Resolution 61/225.

- [Insulin Affordability](https://diabetes.org/tools-resources/affordable-insulin)

## Local

- [BWCA Entry Points](https://www.the-driveby-tourist.com/boundary-waters-canoe-area-outfitters/)
- [Trygg History & Maps](https://trygghistoricalmaps.com/)
- [St Louis MN Homeowner Guide and Links](https://github.com/denisecase/stlouis-mn-homeowner-guide)

## MandArt

- [MandArt (App Store)](https://apps.apple.com/us/app/mandart/id6445924588?mt=12) - runs on MacOS (v12+) - _Released!_
- [MandArt-Docs](https://denisecase.github.io/MandArt-Docs/documentation/mandart/)
- [MandArt-Discoveries](https://github.com/denisecase/MandArt-Discoveries)
- [Color Cube](https://denisecase.github.io/color-cube/)
- [MandArt-Web](https://github.com/denisecase/mandart-web)

## MandArt Supporting

A SwiftUI app for creating custom art with the Mandelbrot set.

- [MandArt: source repo](https://github.com/brucehjohnson/MandArt) 
- [MandArt: my fork](https://github.com/denisecase/MandArt)
- [MandArt deploy](https://github.com/bruceranger/MandArt/)
- [MandArt-Docs: source repo](https://github.com/denisecase/MandArt-Docs)
- [MandMath (w/Julia)](https://github.com/denisecase/MandMath.jl) - Julia enables 150 - 1500+ decimal places
- [Color Cube: source repo](https://github.com/denisecase/color-cube)
- [GrandArt: source repo](https://github.com/denisecase/GrandArt) - explore exponenents beyond 2
- [MandArt3: source repo](https://github.com/denisecase/MandArt3) - explore MandArt with exponenent 3

![MandArt](https://raw.githubusercontent.com/brucehjohnson/MandArt/main/Resources/MandelbrotFigure1024x1024.png)

## Machine Learning

- [Why Do We Square Residuals in Linear Regression?](https://github.com/denisecase/python-ml-linear-regression/)

## NW Diagnostics / Shared

- [nw-diagnostics-python](https://github.com/denisecase/nw-diagnostics-python)
- [datafun-00-python-virtual-env](https://github.com/denisecase/datafun-00-python-virtual-env)

## CI Specs

- [cintel-01-spec](https://github.com/denisecase/cintel-01-spec)
- [cintel-02-spec](https://github.com/denisecase/cintel-02-spec)
- [cintel-03-spec](https://github.com/denisecase/cintel-03-spec)
- [cintel-04-spec](https://github.com/denisecase/cintel-04-spec)
- [cintel-05-spec](https://github.com/denisecase/cintel-05-spec)
- [cintel-06-spec](https://github.com/denisecase/cintel-06-spec)
- [cintel-07-spec](https://github.com/denisecase/cintel-07-spec)
  
## Digital Forensics

- [digital-forensics-resources](https://github.com/denisecase/digital-forensics-resources)
- [386-site](https://github.com/denisecase/386-site)
- [dfir-hash-1](https://github.com/denisecase/dfir-hash-1)
- [dfir-hash-2](https://github.com/denisecase/dfir-hash-2)
- [dfir-pwsh-forensic-copy](https://github.com/denisecase/dfir-pwsh-forensic-copy)
- [dfir-pwsh-file-recovery](https://github.com/denisecase/dfir-pwsh-file-recovery)
- [df-mod6-mobile](https://github.com/denisecase/df-mod6-mobile)

## Local Life

![bear](images/bear.png)
