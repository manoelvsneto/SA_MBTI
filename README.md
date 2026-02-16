# SA_MBTI: MBTI Personality Profiles in Software Architecture Education

## About

This repository contains research materials investigating the relationship between **MBTI (Myers-Briggs Type Indicator) personality types** and **academic performance in Software Architecture courses**. This empirical study analyzes data from 102 students to determine whether personality traits influence learning outcomes in Software Architecture education.

**Research Question:** Does MBTI personality type matter in Software Architecture education and performance?

## Dataset

- **Sample Size**: 102 students from PUCPR's Software Architecture course
- **Variables**: 
  - Class/Year
  - Gender
  - MBTI Type (16 personality types)
  - MBTI Group (Analysts, Diplomats, Explorers, Sentinels)
  - Performance metrics:
    - TDE1: Architecture Requirements (Team-based Development Exercise 1)
    - TDE2: Architecture Requirements (Team-based Development Exercise 2)
    - TDE3: System Development (Team-based Development Exercise 3)
    - Objective Exam Score
    - Final Grade

## Methodology

- **Personality Assessment**: Students completed the 16Personalities test (MBTI-inspired framework)
- **Performance Evaluation**: 
  - Team-based development exercises (TDE): 40% of final grade
  - Individual objective exam: 60% of final grade
- **Statistical Analysis**: Kruskal-Wallis tests with epsilon-squared effect sizes to compare performance across personality groups

## MBTI Groups

Students are classified into four personality groups:
- **Analysts**: Strategic thinkers, innovative problem-solvers
- **Diplomats**: Collaborative, people-focused
- **Explorers**: Practical, action-oriented
- **Sentinels**: Organized, detail-oriented

## Files

- `SBES_MTBI_SA.ipynb` - Statistical analysis notebook (Google Colab compatible)
- `dados.xlsx` - Raw dataset with student performance data
- `data.md` - Formatted dataset table
- `main.tex` - Research paper submitted to SBES 2026 (Brazilian Symposium on Software Engineering)
- `Untitled18.ipynb` - Additional analysis notebook

## Authors

- **Manoel Valerio da Silveira Neto** (ORCID: 0000-0003-0470-5350)
- **Andreia Malucelli** (ORCID: 0000-0002-0929-1874)
- **Sheila Reinehr** (ORCID: 0000-0001-9430-7713)

**Institution**: Graduate Program in Informatics (PPGIa), Pontifical Catholic University of Paraná (PUCPR), Curitiba, PR, Brazil

## Conference

This work has been submitted to:
- **SBES 2026** - Brazilian Symposium on Software Engineering (Education Track)
- **Title**: "Does MBTI Matter in Software Architecture Education?"

## License

Research data and code for academic purposes.
