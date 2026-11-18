# Abdul-Haque Mohammed

Year 13 student studying Maths, Further Maths and Computer Science, aiming for a career in AI/ML engineering. Based in Swansea, UK.

## Summary

- Machine Learning Engineer Intern at CadetX, working on an NLP and forecasting project that predicts AI-company hiring demand from public job postings.
- Did AI engineering work experience at Cadent, where I built a web app powered by a local LLM.
- Completed the Zero To Mastery Complete: AI, Machine Learning and Data Science course and the BCG X Data Science Job Simulation (Forage).
- Focused on doing ML properly: avoiding data leakage, checking results hold up statistically, and picking metrics that fit the problem.

## Selected work

- **[Is DLS Fair in T20 Cricket?](https://github.com/abdulhaquemohammed/dls-fairness-t20)**: Independent project. Analysed 514k deliveries (4,493 T20I/IPL chases) and found DLS undervalues wickets in hand late in a chase (60% vs 47% win rate at par in the last 5 overs), holding up under a match-level bootstrap and a permutation test (p = 0.0003). Built a gradient boosting win-probability model with monotonic constraints (log loss 0.380 vs 0.694 baseline).
- **[Competitor Demand Prediction](https://github.com/abdulhaquemohammed/competitor-demand-prediction)**: CadetX project. Python pipeline collecting 5,000+ job postings from OpenAI, Anthropic, Databricks and NVIDIA via public job-board APIs, with twice-weekly snapshots. Cleaned the text for NLP and built a 158-skill taxonomy to track skill trends, e.g. NVIDIA postings mentioning AI agents rose from 8% to 18%.
- **[Dog Vision: Uncertainty-Aware Breed Classifier](https://github.com/abdulhaquemohammed/dog-vision)**: Transfer learning (MobileNetV2) for 120 dog breeds. The model confidently labelled photos of people as dog breeds, so I added MC dropout: confidence on people fell from 57% to 32% with no loss of dog accuracy (81%). Compared it with temperature scaling (Guo et al., 2017): equal calibration, but better at separating dogs from people (AUROC 0.944 vs 0.907).
- **[Would I Lie to You? Web App](https://github.com/abdulhaquemohammed/would-i-lie-to-you)**: Built during my Cadent placement. Flask app where a local LLM (Llama 3.2 via Ollama) writes the lies, run as a client project (BRD, change requests, UAT) with 37 automated tests.
- **[BCG X Churn Analysis](https://github.com/abdulhaquemohammed/bcg-x-churn-analysis)**: Customer churn model for an energy supplier. Showed the random forest's 90% accuracy hid a 4.6% recall, so it wasn't fit to target a 20% retention discount.

Earlier guided projects from the ZTM course, which I extended: [Bulldozer Price Prediction](https://github.com/abdulhaquemohammed/bulldozer-price-prediction) (0.231 RMSLE with gradient boosting on log prices) and [Heart Disease Classification](https://github.com/abdulhaquemohammed/heart-disease-classification) (84.8% cross-validated accuracy, ~0.93 recall).

## Technical toolkit

Python, NumPy, pandas, scikit-learn, TensorFlow/Keras, Matplotlib, Seaborn, Flask, Ollama, pytest, Jupyter, Google Colab, VS Code, Git/GitHub, Claude Code

## Contact

- LinkedIn: [linkedin.com/in/abdulhaquemohammed](https://www.linkedin.com/in/abdulhaquemohammed/)
