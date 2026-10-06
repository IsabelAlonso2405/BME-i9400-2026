# Meeting 2 — Probability for Diagnosis
## Optional resources

Everything here is **optional**. None of it is assigned, and none of it is examinable beyond what was
covered in the lecture notebook. It is listed because students arrive at this course from very
different backgrounds, and the fastest route to comfort differs by person.

If you only follow one link, make it the first one in "Start here."

Items marked **(free)** are freely readable. Items marked **(CCNY)** are paywalled but available
through the CCNY Libraries — sign in at [library.ccny.cuny.edu](https://library.ccny.cuny.edu/)
or use the campus network. Ask me if you hit a wall; I can supply a PDF.

---

## Start here

| Resource | Why this one | Time |
|---|---|---|
| **[The medical test paradox](https://www.youtube.com/watch?v=lG4VkPoG3ko)** — 3Blue1Brown **(free)** | The single best explanation of today's lecture. Builds the same screening result visually, and arrives at the natural-frequency picture and likelihood ratios independently. Watch this if the 4.5% still feels wrong. | 21 min |
| **[Statistics Notes: Diagnostic tests 1 — sensitivity and specificity](https://doi.org/10.1136/bmj.308.6943.1552)** — Altman & Bland, *BMJ* 1994 **(free)** | One page. The canonical statement of the definitions, written for clinicians. Read alongside part 2 below. | 10 min |
| **[Statistics Notes: Diagnostic tests 2 — predictive values](https://doi.org/10.1136/bmj.309.6947.102)** — Altman & Bland, *BMJ* 1994 **(free)** | The companion page, on PPV and NPV and their dependence on prevalence. Together these two pages are the whole of sections 1 and 6 of the lecture, in the primary literature. | 10 min |

> Both *Statistics Notes* are also on PubMed Central without a paywall:
> [part 1](https://pmc.ncbi.nlm.nih.gov/articles/PMC2540489/) ·
> [part 2](https://pmc.ncbi.nlm.nih.gov/articles/PMC2540558/)

---

## Conditional probability and Bayes' rule

For strengthening the underlying probability rather than the clinical application.

| Resource | Why this one | Time |
|---|---|---|
| **[Introduction to Probability](http://probabilitybook.net/)** — Blitzstein & Hwang, chapter 2 **(free)** | Full textbook, free PDF. Chapter 2 covers conditional probability, the law of total probability, and Bayes' rule at exactly our level, and works the disease-testing example we did. The best single reference if you want the material done properly. | 2–3 h |
| **[Statistics 110: Probability](https://www.youtube.com/playlist?list=PL2SOU6wwxB0uwwH80KTQ6ht66KWxbzTIo)** — Harvard, Joe Blitzstein **(free)** | The lecture course the book accompanies. **Lectures 3 and 4** cover today's material. Blitzstein is an unusually good lecturer; if you prefer being talked through it, start here instead of the book. | 2 × 50 min |
| **[Seeing Theory — Bayesian Inference](https://seeing-theory.brown.edu/bayesian-inference/index.html)** **(free)** | Interactive visualisations from Brown. Drag the sliders and watch the posterior move. Useful if the algebra is fine but the intuition is not. | 20 min |
| **[Bayes' theorem, the geometry of changing beliefs](https://www.youtube.com/watch?v=HZGCoVF3YvM)** — 3Blue1Brown **(free)** | Bayes as areas rather than formulas. The companion to the video above, and worth watching first if you have never seen Bayes at all. | 15 min |
| **[Bayes' rule](https://www.statlect.com/fundamentals-of-probability/Bayes-rule)** — StatLect **(free)** | A compact written reference with worked exercises. Good for a quick refresher rather than a first pass. | 20 min |

---

## Likelihood ratios

The part of the lecture with the least coverage in most introductory texts.

| Resource | Why this one | Time |
|---|---|---|
| **[Likelihood ratios](https://www.cebm.ox.ac.uk/resources/ebm-tools/likelihood-ratios)** — Oxford Centre for Evidence-Based Medicine **(free)** | Short, practical, and written for people who use likelihood ratios in the clinic rather than derive them. Includes the interpretation thresholds quoted in the lecture. | 15 min |
| **[Simple tools for understanding risks: from innumeracy to insight](https://doi.org/10.1136/bmj.327.7417.741)** — Gigerenzer & Edwards, *BMJ* 2003 **(free)** | The argument for natural frequencies — the 1,000-women picture from section 5 — as a general tool. Short, readable, and it will change how you present risk numbers for the rest of your career. | 25 min |

---

## Why this matters: base rates in clinical practice

Optional, and the most interesting reading here if you are going into anything clinical. The lecture
claimed that confusing $P(T{=}1 \mid D{=}1)$ with $P(D{=}1 \mid T{=}1)$ is a common error. These are
the studies behind that claim.

| Resource | Why this one | Time |
|---|---|---|
| **[Interpretation by Physicians of Clinical Laboratory Results](https://doi.org/10.1056/NEJM197811022991808)** — Casscells, Schoenberger & Graboys, *NEJM* 1978 **(CCNY)** | The original result. Staff and students at Harvard Medical School were asked our exact question with a 1-in-1000 prevalence; most answered 95% instead of about 2%. Two pages. | 10 min |
| **[Medicine's Uncomfortable Relationship With Math](https://doi.org/10.1001/jamainternmed.2014.1059)** — Manrai et al., *JAMA Internal Medicine* 2014 **(CCNY)** | The replication, 36 years later, at Boston-area teaching hospitals. The result had not improved. Read it after the 1978 paper. | 15 min |
| **[Helping Doctors and Patients Make Sense of Health Statistics](https://doi.org/10.1111/j.1539-6053.2008.00033.x)** — Gigerenzer et al., *Psychological Science in the Public Interest* 2007 **(CCNY)** | Book-length treatment of the whole problem: what goes wrong, why, and what representations fix it. Skim the sections that interest you rather than reading it end to end. | long |

---

## Source of the numbers used in the lecture

| Resource | Why this one |
|---|---|
| **[National Performance Benchmarks for Modern Screening Digital Mammography](https://doi.org/10.1148/radiol.2016161174)** — Lehman et al., *Radiology* 2017 **(CCNY)** | Where the 86.9% sensitivity, 88.9% specificity, and 4.4% observed PPV come from: 1,682,504 screening mammograms, 359 radiologists, 2007–2013. Worth looking at Table 3 even if you read nothing else, to see how much these numbers vary by age and breast density. |

---

## Looking ahead

The four-outcome table from section 1 returns in **Meeting 9** as the confusion matrix, and the
threshold figure from section 8 becomes the ROC curve. The third *Statistics Notes* paper —
**[Diagnostic tests 3: receiver operating characteristic plots](https://doi.org/10.1136/bmj.309.6948.188)**
**(free)** — is the bridge, and you may want to save it until then.

---

*Broken link, or something here you found useful that is not listed? Email me and I will update this
document.*
