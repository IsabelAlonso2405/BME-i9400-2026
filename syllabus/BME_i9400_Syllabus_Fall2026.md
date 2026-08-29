# BME i9400 — Special Topics in Machine Learning
## Fall 2026

> Formatted version: `syllabus_2026.html` → `BME_i9400_Syllabus_Fall2026.pdf`

| | |
|---|---|
| **Instructor** | Jacek Dmochowski, PhD · jdmochowski@ccny.cuny.edu |
| **Office** | Steinman Hall 460 · hours TBA |
| **Meetings** | Mon & Wed 11:00–12:15 · 28 total · Steinman Hall C-51 |
| **Credits** | 3 |
| **Runtime** | Google Colab |
| **Platform** | github.com/dmochow/BME-i9400-2026 · Brightspace |

---

## About this course

This is a hands-on graduate course in biomedical machine learning. You will learn to frame a biomedical question as a learning problem, build a defensible baseline, adapt a modern model, and evaluate the result with the rigor that biomedical use demands.

It is deliberately not an encyclopedic survey of algorithms, nor a course in training frontier models from scratch. Implementation is easy now. What remains hard — and what this course is about — is data readiness, leakage-free evaluation, model choice, calibration, and interpreting what the model learned. 

**Prerequisites:** basic Python, and prior exposure to probability/statistics and linear algebra. No previous machine learning course is required.

> 
> **Generative AI is permitted and expected on out-of-class work.** That is how you will work in your career. What is graded is not the artifact but your ability to defend it, in class.
>


## Learning outcomes

By the end of the course you will be able to:

1. Frame a biomedical question as a prediction task, stating explicitly what a row of *X* is and what *y* is.
2. Build reproducible, leakage-free train/validation/test workflows and spot the data-quality risks that threaten them.
3. Select metrics and operating thresholds suited to the use case, accounting for imbalance and prevalence.
4. Build, regularize, and interpret linear-model and tree-ensemble baselines.
5. Train neural networks in PyTorch and adapt pretrained image, signal, and text models rather than treat them as black boxes.
6. Determine what a model learned via coefficient, permutation, and gradient-based attribution.
7. Determine whether an effect is real via bootstrap confidence intervals and paired model comparison.

## How the course runs

Two meeting types, planned as alternating but will likely not always be due to time restrictions. 

**Concept meeting.** Conventional lectures, sometimes including one or more short quizzes (tentatively planned to be delivered over Brightspace.)

**Studio meeting.** Twenty minutes of targeted instruction followed by forty-five minutes of in-class Python notebook assignments.


## Assessment

| Component | | Notes |
|---|---:|---|
| In-class quizzes | 10% | About 15 across the semester, scored 0/1/2; your best 10 count. |
| Labs & defense quizzes | 20% | Three labs, released and defended roughly two weeks apart. AI is permitted on the lab. Each is defended by a ten-minute, closed-AI, in-class quiz worth 70% of the component. |
| Midterm exam | 20% | **Wednesday, October 28.** 75 minutes, closed book, pencil and paper exam. |
| Final concept exam | 15% | **Final examination period, Dec 15–21.** 45 minutes, closed book, pencil and paper exam. |
| Capstone project | 35% | An individual end-to-end study built from an instructor-supplied topic. Oral presentation and live Q&A 20%; written report 15%. Full details released during the course. |
| **Total** | **100%** | |

There are no conventional graded homework sets. The three labs are graded primarily through in-class defense, not through the submitted code.


## Policies

**Attendance.** This is a studio course; the work happens in the room. Attendance is not graded directly, but quiz credits can only be earned in class. Your five dropped quizzes are the absence allowance — use them for illness, conferences, and interviews. Please do not email after the fact to explain a missed meeting.

**Late work.**  Lab notebooks may be up to 48 hours late with a 20% penalty on the notebook portion, but *defense quizzes cannot be made up* except for a documented excused absence. Capstone milestones lose 20% per day. Documented medical and emergency exceptions are handled case by case.

**Exam conflicts.** Notify the instructor at least one week in advance of any documented conflict with an exam date.

**Academic integrity.** Discussion of studio work is encouraged; submitted notebooks must be individually authored. Violations of the CCNY Academic Integrity Policy are reported and may result in course failure.

**Accessibility.** Students requiring accommodations should contact the AccessAbility Center (NAC 1/218) and notify the instructor early in the term.

## Materials

A laptop with a modern browser, a Google account for Colab, and a CUNY Brightspace account. Notebooks and curated public datasets are supplied. Colab is the required runtime and all graded work assumes it; a local Python setup is optional and unsupported. 

## Schedule (subject to change)


| # | Date | Type | Topic | Milestone |
|---:|---|---|---|---|
| 1 | Mon 8/31 | Asynchronous | Course launch, Colab setup, and biomedical data readiness: provenance, label quality, splits, leakage | |
| 2 | Wed 9/2 | Concept | Probability for diagnosis: Bayes, prevalence, sensitivity/specificity, PPV/NPV, likelihood ratios | |
| 3 | Wed 9/9 | Studio | Screening simulation; NumPy and pandas on-ramp | |
| 4 | Mon 9/14 | Concept | Linear algebra for ML: vectors, projection, SVD, PCA, embeddings | |
| 5 | Wed 9/16 | Studio | PCA of a biomedical feature matrix | |
| 6 | Wed 9/23 | Concept | Regression: least squares, normal equations, the geometric view, the noise model | |
| 7 | Mon 9/28 | Studio | Fit, regularize, and diagnose a regression baseline | **Lab 1 released** |
| 8 | Wed 9/30 | Concept | Linear classification I: logistic regression, cross-entropy, decision boundaries | |
| 9 | Mon 10/5 | Concept | Linear classification II: confusion matrix, ROC and PR curves, thresholds, imbalance | |
| 10 | Wed 10/7 | Studio | An end-to-end clinical tabular classifier | **Lab 1 defense** |
| 11 | **Tue 10/13** | Concept | Regularization and cross-validation: L1/L2, bias–variance, leakage inside CV | **Monday schedule** |
| 12 | Wed 10/14 | Studio | Nested cross-validation and calibration | |
| 13 | Mon 10/19 | Concept | Optimization and generalization: GD/SGD, learning rates, loss surfaces, convergence | |
| 14 | Wed 10/21 | Studio | Diagnosing underfit, overfit, and unstable training runs | **Lab 2 released** |
| 15 | Mon 10/26 | Review | Synthesis and midterm review | |
| 16 | **Wed 10/28** | Exam | **Midterm examination** | |
| 17 | Mon 11/2 | Concept | Neural networks: the MLP, forward and backward pass, capacity, regularization | |
| 18 | Wed 11/4 | Studio | A PyTorch MLP on clinical tabular data | **Capstone briefs released · Lab 2 defense** |
| 19 | Mon 11/9 | Concept | Trees, ensembles, and attribution: random forests, gradient boosting, permutation importance, SHAP | |
| 20 | Wed 11/11 | Studio | Is the difference real? Bootstrap confidence intervals and paired model comparison | **Capstone brief selection due** |
| 21 | Mon 11/16 | Concept | Convolutional networks: convolution, receptive fields, pooling, transfer learning | |
| 22 | Wed 11/18 | Studio | Fine-tuning a small image encoder on a curated biomedical task; Grad-CAM | **Lab 3 released** |
| 23 | Mon 11/23 | Combined | Sequence models for biosignals: windowed features versus 1D-CNN and GRU on ECG/EEG | **Capstone analysis plan due** |
| 24 | Mon 11/30 | Combined | Text, embeddings, and pretrained encoders; attention conceptually | |
| 25 | Wed 12/2 | Combined | Biomedical LLM workflows: prompting, structured extraction with schema validation, auditing outputs | **Lab 3 defense** |
| 26 | Mon 12/7 | Clinic | Capstone clinic: baselines reproduced, results tables reviewed, peer critique | |
| 27 | Wed 12/9 | Present | Capstone presentations I | 8 min + 4 min graded Q&A |
| 28 | Mon 12/14 | Present | Capstone presentations II | 8 min + 4 min graded Q&A |
| — | **Dec 15–21** | Exam | **Final concept exam** (45 min) and capstone presentations III | **Written package due** |

---

*All information in this syllabus is subject to change at the instructor's discretion.*
