## Dominik Vollbracht

Psychologist and statistician in Karlsruhe, Germany. I build statistical
models and the tooling around them: from measurement models in Stan to
automated reporting pipelines that run in production.

Research associate at RPTU Kaiserslautern-Landau. PhD thesis on visual
analogue vs. Likert-type scales submitted, defense in February 2027.
Completed the qualification program of the DFG Research Training Group
[*Statistical Modeling in Psychology*](https://www.uni-mannheim.de/smip/) (SMiP), 2023–2026.

**Open to roles in applied statistics and data science from April 2027.**

### Featured projects

| Project | What it is |
|---|---|
| [**setanalysis**](https://github.com/donvollb/setanalysis) · [docs](https://donvollb.github.io/setanalysis/) | R package for personalized survey reports with Quarto and Typst: many tailored PDF reports from a single template. In production for the course evaluation at RPTU. Snapshot tests, pkgdown, GitHub Actions. *(Docs in German, [README in English](https://github.com/donvollb/setanalysis/blob/main/README.en.md))* |
| [**set-template**](https://github.com/donvollb/set-template) | Quarto template and end-to-end example for setanalysis, from the survey export to distributed PDFs. All example reports are rendered and checked in CI. |
| [**birmrssim**](https://github.com/donvollb/birmrssim) · [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20305322.svg)](https://doi.org/10.5281/zenodo.20305322) | Simulation tools for the Beta Item Response Model with Response Styles (BIRM-RS), the model we developed in my PhD project: data generation, Stan models, parallel parameter-recovery studies on an HPC cluster. |

### Interactive apps

Shiny apps that run in the browser via shinylive, without a server:

- [BIRM-RS](https://donvollb.github.io/birm-rs_shiny/): our extension of the beta item response model; shows how person, item and response-style parameters shape responses on visual analogue scales
- [Zero- and one-inflated BIRM-RS](https://donvollb.github.io/birm-rs-inflation_shiny/): proof of concept for a proposed extension to responses at the scale endpoints
- [Likert vs. visual analogue scales](https://donvollb.github.io/scale_comp/): how mapping latent values onto a few categories changes variances
- [CFA visualization](https://donvollb.github.io/cfa_shiny/) (German, for teaching): factor loadings, intercepts and residual variances

### Toolbox

**Statistics (main focus):** psychometrics (questionnaire development,
exploratory and confirmatory factor analysis, measurement invariance, IRT,
incl. IRT models for bounded continuous data) ·
multilevel models and multilevel SEM · intensive longitudinal data
(ambulatory assessment, DSEM) · structural equation modeling (path
analysis, latent growth curve, change and state models) · linear and
generalized linear models (incl. logistic and multinomial regression) ·
latent class and profile analysis · Bayesian modeling · experimental
design and power analysis · simulation studies<br>
**Code:** R (packages, Shiny and shinylive), Stan, Quarto (parameterized
reports, templates and extensions, reproducible manuscripts incl. my
dissertation, presentations, websites), Typst, Git and GitHub Actions,
HPC with Slurm · SQL and Python basics<br>
**Surveys:** questionnaire design, LimeSurvey (incl. API), EvaSys,
LLM-based analysis of open-ended responses

### Contact

[Website](https://donvollb.github.io/) ·
[LinkedIn](https://www.linkedin.com/in/dominik-vollbracht/) ·
[ORCID](https://orcid.org/0000-0003-1040-7851) ·
[dominik@vollbracht.email](mailto:dominik@vollbracht.email)
