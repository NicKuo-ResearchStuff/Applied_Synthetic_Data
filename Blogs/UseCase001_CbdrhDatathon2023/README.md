# The CBDRH Health Data Science Datathon 2023:</br> Learning, Collaboration, and Innovation through Synthetic Data

<img src="Supporting_Images/EFig03_CbdrhHealthDatathon.png" width="600"/>

*Photo courtesy of CBDRH UNSW*

---

## Overview

The [CBDRH Health Data Science Datathon 2023](https://cbdrh-hds-datathon-2023.github.io/) brought together students, mentors, and government partners for a full day of hands-on data exploration.</br>
On 2023-05-26, twenty-two students worked in six teams (five in person and one hybrid) to analyse the Antiretroviral Therapy (ART) for HIV synthetic dataset from [the Health Gym AI](https://github.com/NicKuo-ResearchStuff/Health_Gym_AI/tree/main/).

This event exemplified how realistically complex synthetic datasets can bridge the gap between classroom learning and real-world data science, all while preserving privacy and reproducibility.

---

## The Challenge

Participants were invited to pose their own research questions and develop complete analytical pipelines -- from exploratory analysis to model design and presentation.</br>
Expert mentors from the CBDRH and NSW Health (Sydney Local Health District) guided teams throughout the day, supporting both clinical interpretation and technical modelling decisions.

While competition was part of the fun, the day’s emphasis lay in collaboration, curiosity, and creativity -- with students applying the full spectrum of skills learned in the Health Data Science program.

---

## The Dataset

Teams worked with [the Synthetic ART for HIV dataset](https://github.com/NicKuo-ResearchStuff/Health_Gym_AI/tree/main/Blogs/Blogs001_Intro), a [Generative Adversarial Network (GAN)-based synthetic dataset](https://www.sciencedirect.com/science/article/pii/S1532046423001570) containing:

| Data Type                | Example Fields                              |
| ------------------------ | ------------------------------------------- |
| **Patient Demographics** | `patient_id`, `age`, `sex`, `ethnicity`     |
| **Clinical Markers**     | `viral_load`, `CD4_count`, `follow_up_time` |
| **Drug Regimens**        | `FTC+TDF`, `3TC+ABC`, `DRV+FTC+TDF`, `DTG`  |
| **Treatment Dynamics**   | longitudinal regimen changes and outcomes   |

The dataset simulates 8,916 synthetic patients and provides a privacy-preserving, yet biologically plausible, environment for machine learning and statistical modelling.
Because the data are synthetic, participants could explore HIV treatment dynamics freely — without ethics approval or confidentiality concerns.

---

## Innovation in Action

The teams’ work highlighted the versatility of synthetic health data:

* <ins>Winning Team:</ins> Deployed a neural network to predict treatment success under different ART combinations.
* <ins>Second Place:</ins> Used survival analysis to identify the most effective regimen for viral suppression.
* <ins>Third Place:</ins> Examined the impact of Dolutegravir (DTG) as a third-agent drug on time to viral suppression.

Across projects, students explored diverse modelling approaches -- from interpretable survival curves to deep learning -- demonstrating how synthetic data can power both clinical insight and technical innovation.

---

## Why It Matters

This event demonstrates the educational value of synthetic data in practice:

* Enables hands-on learning without ethics restrictions.
* Encourages critical thinking and interdisciplinary teamwork.
* Provides realistic, reproducible datasets for machine learning, statistics, and causal analysis.
* Strengthens partnerships between academia, government, and clinical informatics.

\- Nic

(Last Edit: 2025-11-12)
