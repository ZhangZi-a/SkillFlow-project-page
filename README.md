# SkillFlow Project Page

This repository contains the project page for **SkillFlow: Benchmarking Lifelong Skill Discovery and Evolution for Autonomous Agents**.

The page is built as a lightweight static site based on the Academic Project Page Template and has been customized to present the SkillFlow benchmark, its core motivation, benchmark design, visual assets, main experimental results, and citation information.

## Overview

The current page highlights:

- the SkillFlow title, authors, affiliations, and benchmark summary
- direct links to the GitHub project and HuggingFace dataset
- benchmark visuals, including the overview figure, construction pipeline, taxonomy, and DAEF example
- the main experimental results table
- key findings from the paper
- a BibTeX entry for citation

## Project Structure

- `index.html`: main page content and section layout
- `static/css/index.css`: custom styling for the project page
- `static/js/index.js`: page interactions such as copy button, dropdown, and scroll-to-top behavior
- `static/images/`: local image assets used by the page

Key image assets currently used include:

- `static/images/logo2.png`
- `static/images/skillflow.png`
- `static/images/data_pipeline.png`
- `static/images/data_taxonomy.png`
- `static/images/daef_example.png`

## Local Preview

You can preview the page locally with a simple static server:

```bash
python3 -m http.server 8000
```

Then open:

```bash
http://127.0.0.1:8000
```

## External Links

The current page includes the following public links:

- GitHub: `https://github.com/ZhangZi-a/SkillFlow`
- HuggingFace: `https://huggingface.co/datasets/zhang-ziao/SkillFlow-Task`

## Acknowledgment

This project page is adapted from the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template), which was originally inspired by the [Nerfies](https://nerfies.github.io/) project page.
