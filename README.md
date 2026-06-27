# Khaled Alnuaimi

AI researcher · financial NLP · multimodal affect &amp; deception analysis · PhD candidate (AI), Khalifa University · CFA charterholder

[Google Scholar](https://scholar.google.com/citations?user=jjOt0IoAAAAJ) · [LinkedIn](https://www.linkedin.com/in/khaled-alnuaimi-cfa-2187b7148)

I treat central-bank and corporate communication as a multimodal signal: what speakers say, how they hedge or evade under questioning, and what their face and delivery reveal that the transcript does not. I build interpretable models and benchmarks for evasion and discourse analysis in financial Q&amp;A — FOMC press conferences, earnings calls — and I work on multimodal video+text understanding and LLM-as-judge evaluation. The through-line: turn affect, pragmatics, and deception cues into measurable, falsifiable signals.

**Now (2026):** finishing a PhD on agent-based financial question generation; building autonomous, validation-gated research-and-trading systems; incoming Visiting Researcher at Tsinghua SIGS (Sep 2026).

## Research

Financial NLP and central-bank communication:

| Paper | Venue / Year | What it shows |
|---|---|---|
| Multi-modal Understanding of FOMC Press Conferences for Question Generation via Visual and Textual Cues | IEEE Access, 2025 | FOMC-QA, a ~40h multimodal video+transcript dataset; Vision-Language Models beat text-only LLMs at financial question generation by exploiting visual grounding. |
| Detecting Evasive Answers in Financial Q&amp;A: A Psychological Discourse Taxonomy and Lightweight Baselines | FinNLP Workshop @ EMNLP 2025 | A deception-psychology taxonomy and interpretable baselines (hedges, tense, embedding alignment) for evasive-answer detection on annotated earnings-call Q&amp;A. |
| Evasive Answers in Financial Q&amp;A: Earnings Calls vs. FOMC Press Conferences | NeurIPS 2025 Workshop on Generative AI in Finance | A three-level psychology/pragmatics taxonomy and lightweight baselines, comparing evasion in earnings calls vs. FOMC press conferences. |
| Enriching Datasets with Demographics through Large Language Models: What's in a Name? | Preprint, 2024 ([arXiv:2409.11491](https://arxiv.org/abs/2409.11491)) | Zero-shot LLMs match or beat bespoke supervised models at name-based demographic enrichment; surfaces systematic LLM biases (notably age underestimation). |
| Mapping Hong Kong's Financial Ecosystem: A Network Analysis of the SFC's Licensed Professionals and Institutions | Complex Networks 2024 | Network analysis of Hong Kong's licensed financial professionals and institutions. |

Computer vision — detection, tracking, and face analysis:

| Paper | Venue / Year | What it shows |
|---|---|---|
| EfficientFaceV2S: A Lightweight Model and a Benchmarking Approach for Drone-Captured Face Recognition | Expert Systems with Applications, 2025 | A lightweight model and benchmark for face recognition on drone-captured imagery. |
| ELTrack: Events-Language Description for Visual Object Tracking | IEEE Access, 2025 | Language-described, event-based visual object tracking. |
| Multi-scale Hierarchical Contour Framework for Detecting Cluttered Threats in Baggage Security | IEEE Access, 2024 | A multi-scale contour framework for detecting cluttered threats in X-ray baggage. |
| Autonomous Drone-Person Tracking and Following in Uniform Appearance Scenarios | ECCV 2024 Workshops | Drone-based person tracking and following under uniform-appearance conditions. |
| Integrating Vision-Language Supervision for Uniform Appearance Tracking | IEEE ICIP 2024 | Vision-language supervision for tracking targets of near-identical appearance. |
| Detection Transformer Framework for Recognition of Heavily Occluded Suspicious Objects | IEEE CIVEMSA 2023 | A DETR-based framework for recognizing heavily occluded suspicious objects. |

Earlier work:

| Paper | Venue / Year | What it shows |
|---|---|---|
| Deep Learning-Based Health Monitoring for Photovoltaic Systems | IEEE Journal of Photovoltaics, 2025 | A two-stage UAV-imagery pipeline (SegFormer segmentation + YOLOv8 anomaly detection) for PV health monitoring. My MSc thesis work. [code](https://github.com/khshalnuaimi/pv-health-monitoring) |

Several manuscripts on FOMC/ECB communication, facial-behavior benchmarks, and discourse modeling are under review.

## Systems

| Repo | What it is |
|---|---|
| [sentiment-analysis-benchmark](https://github.com/khshalnuaimi/sentiment-analysis-benchmark) | A reproducible, leak-free NLP benchmark comparing classical ML, a from-scratch LSTM, and DistilBERT for sentiment classification on IMDB — negation-aware preprocessing, train-only vocabularies, consistent timing. |
| [pv-health-monitoring](https://github.com/khshalnuaimi/pv-health-monitoring) | Official implementation of my IEEE Journal of Photovoltaics paper — a two-stage SegFormer + YOLOv8 pipeline for UAV-based solar-panel segmentation and anomaly detection. |
| [equity-statistics](https://github.com/khshalnuaimi/equity-statistics) | A statistical toolkit for equity returns — exploratory analysis, Student-t confidence intervals, CAPM beta, hypothesis tests, and Markowitz portfolios on public market data. |
| [tda-market-crashes](https://github.com/khshalnuaimi/tda-market-crashes) | Topological data analysis of financial time series — a persistent-homology regime-stress signal on index returns, reproducing Gidea & Katz (2018) on public data. |
| [pairs-trading](https://github.com/khshalnuaimi/pairs-trading) | Statistical pairs trading from scratch — distance (SSD) and Engle–Granger cointegration pair selection, z-score signals, and a look-ahead-free backtest on public data, with a study comparing both selection families. |
| [hierarchical-risk-parity](https://github.com/khshalnuaimi/hierarchical-risk-parity) | A from-scratch implementation of López de Prado's Hierarchical Risk Parity — correlation clustering, quasi-diagonalization, recursive bisection — with a five-task S&amp;P 500 sector study on public data. |

More to come — agentic-LLM and autonomous-systems work, published as it's cleaned up. Some autonomous-systems research stays private; details on request.

## Stack

Python · PyTorch · Hugging Face Transformers · LLM agents (RAG, LoRA / instruction tuning, LLM-as-judge) · vision-language &amp; multimodal models · cvxpy / scipy portfolio optimization · purged walk-forward backtesting · LaTeX.

## Contact

[LinkedIn](https://www.linkedin.com/in/khaled-alnuaimi-cfa-2187b7148) · [Google Scholar](https://scholar.google.com/citations?user=jjOt0IoAAAAJ)
