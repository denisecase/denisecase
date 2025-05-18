# Welcome

## Applied Guides: Getting Started with Computer Basics

- [applied-computer-organization](https://github.com/denisecase/applied-computer-organization/)

## Applied Guides: Professional Python for Analytics

Project Setup / Initialization / Standard Workflow
- ⭐[pro-analytics-01](https://github.com/denisecase/pro-analytics-01)
- 🆕[pro-analytics-01-audio-guides](https://github.com/denisecase/pro-analytics-01-audio-guides) - AI generated two-person podcasts discussing professional Python for analytics
- 🆕[Listen](https://denisecase.github.io/pro-analytics-01-audio-guides/)

Apache Kafka / Spark Starter Template
- [pro-analytics-apache-starter](https://github.com/denisecase/pro-analytics-apache-starter) - keep JDK, JAVA_HOME, etc isolated

## Example of Building an LLM AI System to Help with Pro-Analytics-01

- [pro-analytics-ai](https://github.com/denisecase/pro-analytics-ai) — illustrates how LLMs like ChatGPT work by creating an AI assistant trained on [pro-analytics-01](https://github.com/denisecase/pro-analytics-01). It uses APIs (OpenAI/OpenRouter) to process user prompts and generate natural language responses, but all retrieval and context selection is performed locally based on the source repository text.
- The AI assistant runs locally on a 2 TB SSD machine with 12/24 cores, using API calls (via a free OpenRouter API key).
- The frontend is lightweight, but the backend uses a local retrieval pipeline (ChromaDB + sentence-transformers) that depends on large Python ML libraries, making it too heavy for serverless platforms like AWS Lambda and significant even for AWS EC2.
- Even when calling external APIs (and not hosting full LLM models), generating embeddings and performing document retrieval requires a significant machine learning environment.
- When we **build a brain** by indexing our own documents, the storage, memory, and processing requirements expand dramatically.

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

## Applied Machine Learning

- [applied-ml-template](https://github.com/denisecase/applied-ml-template) - copy this to your GH and replace template with yourname
- [ml-04](https://github.com/denisecase/ml-04) - classification analysis
- [ml-07](https://github.com/denisecase/ml-07) - regression analysis

## Data Analytics Fundamentals

- [applied-computer-organization](https://github.com/denisecase/applied-computer-organization/)
- [pro-analytics-01](https://github.com/denisecase/pro-analytics-01)
- [datafun-01-textbook](https://github.com/denisecase/datafun-01-textbook) - requires virtual environment and installed packages
- [datafun-01-utils](https://github.com/denisecase/datafun-01-utils) - first reusable module w/stats
- [datafun-02-project-setup](https://github.com/denisecase/datafun-02-project-setup) - scripting project folders
- [datafun-03-analytics](https://github.com/denisecase/datafun-03-analytics) - fetch and write data, read and process it
- [datafun-04-notebooks](https://github.com/denisecase/datafun-04-notebooks) - explore/present insights using Python and Markdown in a Jupyter notebook
- [datafun-05-sql](https://github.com/denisecase/datafun-05-sql) - Python and SQL
- [datafun-05-spec](https://github.com/denisecase/datafun-05-spec)
- [datafun-06-spec](https://github.com/denisecase/datafun-06-spec) - Custom EDA 
 
## Smart Sales 

- [smart-sales-analysis-goals](https://github.com/denisecase/smart-sales-analysis-goals)
- [smart-sales-raw-data](https://github.com/denisecase/smart-sales-raw-data)
- [smart-sales-starter-files](https://github.com/denisecase/smart-sales-starter-files)
- [smart-sales-docs](https://github.com/denisecase/smart-sales-docs)
- [smart-sales-olap](https://github.com/denisecase/smart-sales-olap)
- [smart-sales-spark](https://github.com/denisecase/smart-sales-spark)
- [smart-sales-duckdb-sql](https://github.com/denisecase/smart-sales-duckdb-sql)
- [smart-sales-duckdb-sql-python](https://github.com/denisecase/smart-sales-duckdb-sql-python)

## Streaming Data

- [buzzline-01-case](https://github.com/denisecase/buzzline-01-case) - Python generators for streaming pipelines
- [buzzline-02-case](https://github.com/denisecase/buzzline-02-case) - Kafka pipelines for streaming data
- [buzzline-03-case](https://github.com/denisecase/buzzline-03-case) - Kafka pipelines for streaming structured and semi-structured data
- [buzzline-04-case](https://github.com/denisecase/buzzline-04-case) - Kafka pipelines with live visualizations
- [buzzline-05-case](https://github.com/denisecase/buzzline-05-case) - Kafka pipelines with data storage
- [kafka-producer-earthquake](https://github.com/denisecase/kafka-producer-earthquake) - Kafka producer for streaming earthquake data from USGS API
- [dc-mailer](https://github.com/denisecase/dc-mailer)
- [dc-texter](https://github.com/denisecase/dc-texter)

## Xcode 15 and GitHub

- [Guide: Save Your SwiftUI Project Progress to GitHub Using XCode 15+](https://github.com/denisecase/guide-xcode-to-github)

## World Diabetes Day - November 14

[World Diabetes Day (WDD)](https://worlddiabetesday.org/) is the world’s largest diabetes awareness campaign reaching a global audience of over 1 billion people in over 160 countries.
It is marked every year on 14 November, the birthday of Sir Frederick Banting, who co-discovered insulin along with Charles Best in 1922.

WDD was created in 1991 by International Diabetes Federation (IDF) and the World Health Organization and became an official United Nations Day in 2006 with the passage of United Nations Resolution 61/225.

- [Insulin Affordability](https://diabetes.org/tools-resources/affordable-insulin)

## Local

- [BWCA Entry Points](https://www.the-driveby-tourist.com/boundary-waters-canoe-area-outfitters/)
- [Trygg History & Maps](https://trygghistoricalmaps.com/)

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

## Continuous Intelligence and Interactive Analytics

- [cintel-01-spec](https://github.com/denisecase/cintel-01-spec)
- [cintel-02-spec](https://github.com/denisecase/cintel-02-spec)
- [cintel-03-spec](https://github.com/denisecase/cintel-03-spec)
- [cintel-04-spec](https://github.com/denisecase/cintel-04-spec)
- [cintel-05-spec](https://github.com/denisecase/cintel-05-spec)
- [cintel-06-spec](https://github.com/denisecase/cintel-06-spec)
- [cintel-07-spec](https://github.com/denisecase/cintel-07-spec)
- [fetch-data-weather](https://github.com/denisecase/fetch-data-weather)

## NW Diagnostics / Shared

- [nw-diagnostics-python](https://github.com/denisecase/nw-diagnostics-python)
- [datafun-00-python-virtual-env](https://github.com/denisecase/datafun-00-python-virtual-env)

## Continuous Intelligence and Interactive Analytics

- [pyshiny-tips-dashboard-express](https://github.com/denisecase/pyshiny-tips-dashboard-express)
- [pyshiny-penguins-dashboard-express](https://github.com/denisecase/pyshiny-penguins-dashboard-express)
- [pyshiny-penguins-dashboard-core](https://github.com/denisecase/pyshiny-penguins-dashboard-core)
- [cintel-01-getting-started](https://github.com/denisecase/cintel-01-getting-started)
- [cintel-02-app](https://github.com/denisecase/cintel-02-app)
- [cintel-03-data](https://github.com/denisecase/cintel-03-data)
- [cintel-04-reactive](https://github.com/denisecase/cintel-04-reactive)
- [cintel-05-live-updates](https://github.com/denisecase/cintel-05-live-updates)
- [cintel-stock-response](https://github.com/denisecase/cintel-stock-response)

## Northwoods

- [Meal Planner](https://denisecase.github.io/meal-planner/)
- [Select and Sort](https://denisecase.github.io/select-and-sort/)
- [Freeze Tracker](https://github.com/denisecase/freeze-tracker)
- [Northwoods](https://github.com/denisecase/Northwoods)
- [JFC](https://github.com/denisecase/johnson-family-cabin)

## Digital Forensics

- [digital-forensics-resources](https://github.com/denisecase/digital-forensics-resources)
- [386-site](https://github.com/denisecase/386-site)
- [dfir-hash-1](https://github.com/denisecase/dfir-hash-1)
- [dfir-hash-2](https://github.com/denisecase/dfir-hash-2)
- [dfir-pwsh-forensic-copy](https://github.com/denisecase/dfir-pwsh-forensic-copy)
- [dfir-pwsh-file-recovery](https://github.com/denisecase/dfir-pwsh-file-recovery)
- [df-mod6-mobile](https://github.com/denisecase/df-mod6-mobile)

## World Quantum Day - April 14

- [World Quantum Day: Questions on Applied QC](https://github.com/denisecase/world-quantum-day-2024)

## Alexa Skills

_Beginner-friendly - 
these skills are great for students to explore GitHub, open-source, and Alexa projects. 
Schedules can be updated with no coding experience - 
follow a link below and look in lambda/games.json to see how easy it is to update the schedule when a new season begins._ 

Skills to ask Alexa about upcoming local games in Ely Minnesota. [❄](https://www.wunderground.com/forecast/us/mn/ely)

- [TimberwolfTracker-BoysBasketball](https://github.com/denisecase/TimberwolfTracker-BoysBasketball)
- [TimberwolfTracker-GirlsBasketball](https://github.com/denisecase/TimberwolfTracker-GirlsBasketball)
- [TimberwolfTracker-GirlsVolleyball](https://github.com/denisecase/TimberwolfTracker-GirlsVolleyball)

## Top Three

- [Top Three](https://github.com/denisecase/top-three)

## ArcDraw

- [ArcDraw source repo](https://github.com/brucehjohnson/ArcDraw) 
- [ArcDraw my fork](https://github.com/denisecase/ArcDraw) 

## Local Life

![bear](images/bear.png)
