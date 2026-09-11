# raphaelyana
![Profile Views](https://komarev.com/ghpvc/?username=raphaelyana&color=blue&style=flat-square) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFCA28?style=flat-square&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

[![My Skills](https://skillicons.dev/icons?i=py,pytorch,sklearn,docker,git,postgres,huggingface)](https://skillicons.dev)

## About Me
I am a graduate student passionate about **Machine Learning**, **AI**, and intellectually stimulating problems. I am completing an MSc in **Computational Statistics and Machine Learning** at *University College London*, after an MEng in **Electrical & Electronic Engineering**, also at *University College London*.  

My background includes research scientist internships in start-ups and scale-ups, with a strong focus on applying theoretical foundations to provide hands-on solutions. I am particularly motivated by the fields of **safety**, **reasoning reliability**, and **alignment** of Large Language Models. My main goal is to have an impact on people's lives.  

---

## Featured Projects

### [Itinerary Planner - 2nd Place at Mistral AI Hackathon](https://github.com/raphaelyana/itinerary_planner)

:trophy: Algorithm used to score 2nd in a Mistral AI hackathon, taking place at the [Palace of Versailles](https://en.wikipedia.org/wiki/Palace_of_Versailles). 

**The Mission**: Use LLM technologies to build a full solution for the Castle so that people can get informations easily (the website is kind of complicated to go through) and build them a personalised itinerary based on the preferences. 

**Challenges**: LLMs do not plan itineraries well. Thus, I came up with an idea to build a graph and optimize the path based on the remaining nodes corresponding to the preferences. Framing it into an Orienteering Problem with Time Windows (which selects the nodes worth to visit under the time budget, not just orders them), I built an OR-Tools solver with guided local search over a graph. Currently extending it with a RL agent benchmarked against the solver.

### [Benchmarking Normative Reasoning in LLMs](https://github.com/raphaelyana/normative_reasoning_and_stereotypes) 

:page_facing_up: **[Benchmarking Aligned Reasoning in Test-Time Constrained AI Systems: Full Write Up](https://github.com/raphaelyana/normative_reasoning_and_stereotypes/blob/main/Yana-MSc-Thesis.pdf).** MSc thesis, University College London X Holistic AI, 2025.

:bar_chart: Datasets: MGSD (stereotype detection), MentalManip (manipulation detection), MMLU (benchmark for several categories), MMLU-Large (narrowing MMLU to 4 categories with more samples, 2 normative and 2 logical reasoning: Professional Law, Moral Dilemmas, College Mathematics, Formal Logic).

**Overview** Master Thesis project for benchmarking LLMs in normative reasoning tasks, by assessing in context-learning strategies and demographic role-play effects. Benchmarks 6 in-context learning strategies across 6 models and 4 datasets. Evaluates GPT-4.1-mini over 60 demographic role-play profiles (along ethnicity, gender and age) through a three-level statistical pipeline, and introduces newly designed consensus-based stability metrics for explaining performance beyond accuracy (COI, ATI, CAI).

**Repository contents**:
- A reproducible cost-aware benchmark;
- A multi-level statistical framework for analysis of demographic and behavioural effects;
- Tools for metrics visualisation;

**Main Results Interpretations**:
- Few-shots with definition reaches approximately ~95% of best strategy's accuracy at half the token cost, it beats complex reasoning;
- Demographic role-playing explains under 3% of the performance variance, and fails to generalise out-of-sample (which challenges the field's focus on debiasing);
- Behavioural patterns can be surfaced by the new consistency-boldness metrics, missed before by accuracy and other metrics.

### [Speaker Extraction](https://github.com/raphaelyana/speaker_extraction) 

A recent project leveraging LLMs to extract from a given book all the sentences spoked by a character. The process keeps track of the book structures and paragraphs numbers within the structure layers, and reports them along with the extracted sentences. Also allows for extracting narration if the character is both a narrator and a speaker (*e.g.* Socrates in The Republic).

<!--  ### [MSc CSML Projects](https://github.com/raphaelyana/csml-portfolio) --->

---

## Areas of Expertise
- **Natural Language Processing**: Python (SpaCy), LLM fine-tuning, transformers, LSTMs  
- **Deep Learning**: Python (PyTorch), representation learning, neural network optimisation
- **Optimisation**: OR-tools, unconstrained methods, constrained methods, and non-smooth methods for convex & non-convex data
- **Unsupervised Learning**: Dimensionality reduction, generative models  
- **Probabilistic Modelling**: Bayesian methods, latent variable models    
- **Reinforcement Learning**: Markov decision processes, dynamic programming, policy/value-based methods  

---

## Education

### University College London (UCL)  
**MSc Computational Statistics and Machine Learning**  
*London, United Kingdom — Sept. 2024 – Sept. 2025*  

- Obtained a Distinction.
- MSc Thesis: *Benchmarking Aligned Reasoning in Test-Time Constrained AI Systems*, focusing on LLM reasoning reliability and evaluation under test-time constraints.

### University College London (UCL)  
**MEng Electrical and Electronic Engineering**  
*London, United Kingdom — Sept. 2020 – June 2024*  

- Obtained a Second Class Honours - Upper Division (High 2:1) 

---

## Technical Skills
**Languages**  
- Python (NumPy, pandas, scikit-learn, PyTorch)  
- C++ (STL containers, memory management)  
- SQL (nested subqueries)  

**Tools & Frameworks**  
- Docker, Git, Jupyter  
- Hugging Face Transformers  
- Visualisation: Matplotlib  

---

## Experience

### AI Score
**Founding AI/ML Engineer**
*London, United Kingdom - Oct. 2025 - Sept. 2026*

- As employee #2 (pre-seed through $5.4M seed), owned ML pipeline end-to-end: full data-curation, training, testing, and MLOps monitoring. Shipped production NLP models on text data.
- Engineered under hard CPU-only, low-latency constraints; built classical NLP feature pipelines; quantized and pruned models.


### Holistic AI  
**Part-time Research Scientist**  
*London, United Kingdom — March 2025 – Sept. 2025*  

- Contributing to two research projects, alongside a separate academic paper based on MSc thesis.  
- Developed reproducible experimental pipelines, data preprocessing workflows, and statistical evaluation scripts in Python to ensure robustness and replicability of results. Collaborated with cross-disciplinary teams, translating technical findings into business-relevant recommendations on ethical AI deployment.    

### Qolaig  
**AI Research Scientist**  
*Paris, France — Jan. 2024 – July 2024*  

- Designed LLM agent automation pipelines across enterprise workflows (customer support, operations, sales) and integrated them into client systems; cut inference costs through caching repeated calls and prompt restructuring to meet client requirements.
- Built a deployment framework for Mistral 7B model, containerised models with Docker and deployed to remote GPUs (Paperspace) for accelerated inference.



<!-- ## I am currently learning 
--- -->



<!-- ## Fun Facts
---
- I always feel bad for not taking some modules, because there are too many choices at univerisity. So I ask my friends to send me all the lecture slides and courseworks materials, and do them on my own in my additional time.
--- -->

<!--
**raphaelyana/raphaelyana** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
