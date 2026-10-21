# vibesense
Vibration-based machine anomaly detection using signal processing and machine learning.
# VibeSense

**Detect the unusual. Understand the signal.**

VibeSense is an ECE + AI/ML project exploring vibration-based anomaly detection for machine health monitoring. It aims to investigate whether patterns in vibration signals can help distinguish normal machine behavior from unusual operating conditions.

> Project status: Initial concept and research planning. Model performance and detection capabilities have not yet been established.

## The problem

Rotating machinery produces vibration signals that reflect its operating behavior. Changes in these signals may indicate unusual conditions. Identifying such patterns is a useful engineering problem at the intersection of sensors, digital signal processing, and machine learning.

## Project objectives

- Explore vibration datasets and understand their signal characteristics.
- Develop a reproducible pipeline for signal inspection and preprocessing.
- Establish a baseline anomaly detection method and compare suitable alternatives.
- Evaluate detection quality, false alarms, and computational considerations.
- Build an interactive dashboard for exploring signals and model outputs.
- Investigate the feasibility of eventual edge deployment on resource-constrained hardware.

## Research questions

1. Which time-domain and frequency-domain features help characterize vibration behavior?
2. How well can a baseline model identify unusual signals on held-out data?
3. How sensitive are detection results to noise, operating conditions, and data imbalance?
4. What trade-offs arise between detection quality and computational cost?

## Proposed workflow

1. **Data:** Identify a suitable public vibration dataset and document its source and usage terms.
2. **Exploration:** Visualize waveforms and inspect signal distributions.
3. **Signal processing:** Explore features such as RMS amplitude, variance, and frequency-domain characteristics where appropriate.
4. **Modeling:** Establish a simple baseline before testing more complex approaches.
5. **Evaluation:** Use a leakage-aware split and appropriate metrics; report false positives and false negatives where labels permit.
6. **Visualization:** Build a dark, teal-accented dashboard for signal exploration and model outputs.
7. **Edge AI:** Assess deployment constraints as a later extension.

## Evaluation plan

Depending on dataset labels and the chosen task, evaluation may include precision, recall, F1-score, confusion matrices, false-alarm rate, and inference time. Any results will be reported only after experiments are conducted. Data splitting will account for possible overlap between recordings or operating conditions to reduce overly optimistic evaluation.

## Planned technology

- Python
- NumPy and pandas
- SciPy and Matplotlib
- scikit-learn
- Jupyter or Google Colab
- Streamlit or a similar dashboard framework (planned)

The final stack may change as the research question becomes more specific.

## Roadmap

- [x] Define project concept and research direction
- [ ] Select and document a public vibration dataset
- [ ] Explore and visualize raw signals
- [ ] Build a baseline anomaly detector
- [ ] Evaluate results and document limitations
- [ ] Develop the interactive dashboard
- [ ] Investigate edge deployment

## Scope and limitations

An anomaly is not automatically a specific mechanical fault. Reliable fault diagnosis requires appropriate data, validation, and domain knowledge. Simulated data may be useful for prototyping, but it cannot establish real-world performance. Hardware deployment and any claims about predictive maintenance remain future work until demonstrated.

## Reproducibility

Experiments will document dataset sources, preprocessing steps, model settings, random seeds where applicable, and evaluation procedures. Dataset licenses and redistribution restrictions will be respected.

## Author

An Electronics and Communication Engineering student exploring the intersection of signal processing, machine learning, and embedded intelligence.

---

*VibeSense is an educational and research-oriented prototype, not a certified industrial safety or predictive-maintenance system.*
