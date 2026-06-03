```mermaid
gantt
    title Research Method Design Project Timeline (Aug 2026 – Jul 2027)
    dateFormat YYYY-MM-DD
    axisFormat %b %Y
    excludes weekends

    section Planning & Research Preparation

    Topic Selection & Scope Definition (4 weeks / 30 days) :p1, 2026-08-01, 30d
    Research Questions & Objectives (2 weeks / 15 days)     :p2, after p1, 15d
    Literature Review & Framework (8 weeks / 60 days)        :p3, after p2, 60d

    Milestone: Proposal Finalised                             :milestone, m1, after p3, 1d

    section Development & System Setup

    Simulation Environment Setup (6 weeks / 45 days)         :p4, after m1, 45d
    Baseline Traffic Control Implementation (6 weeks / 45d)  :p5, after p4, 45d
    Edge AI + IoT Architecture Development (8 weeks / 60d)   :p6, after p5, 60d
    Integration Testing & Debugging (3 weeks / 20 days)       :p7, after p6, 20d

    Milestone: System Ready for Experiments                  :milestone, m2, after p7, 1d

    section Experimentation & Data Collection

    Experiment Design (4 weeks / 30 days)                     :p8, after m2, 30d
    Simulation Runs & Data Collection (8 weeks / 60 days)     :p9, after p8, 60d
    Data Cleaning & Processing (2 weeks / 15 days)            :p10, after p9, 15d

    Milestone: Dataset Completed                              :milestone, m3, after p10, 1d

    section Analysis & Evaluation

    Performance Metrics Calculation (4 weeks / 30 days)      :p11, after m3, 30d
    Comparative Analysis & Testing (4 weeks / 30 days)        :p12, after p11, 30d
    Results Interpretation (2 weeks / 15 days)               :p13, after p12, 15d

    section Writing & Submission

    Thesis Writing (Methodology + Results) (4 weeks / 30d)   :p14, after p13, 30d
    Discussion & Conclusions (3 weeks / 20 days)             :p15, after p14, 20d
    Revision & Proofreading (3 weeks / 20 days)              :crit, p16, after p15, 20d
    Final Formatting & Submission (1 week / 7 days)          :crit, p17, after p16, 7d

    Final Submission                                          :milestone, final, after p17, 1d
```
