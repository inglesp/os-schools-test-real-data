# OS Schools Test (with real data)

## Project overview

This code is being developed for the [Teaching Improvement through Data and Evaluation (TIDE) project](https://niot.org.uk/research-projects/teacher_improvement_through_data_evaluation_tide).
It is being developed locally using [synthetic data](https://github.com/bennettoxford/os-schools-data/tree/main/synthetic-data) before being run against real data in the [Teacher Education Dataset (TED)](https://niot.org.uk/research-projects/teacher_education_dataset).
To ensure public transparency, all requests to run research code against the TED dataset can be found [here](https://github.com/bennettoxford/os-schools-requests/issues?q=label%3Arun-request),
and all requests to share the outputs can be found [here](https://github.com/bennettoxford/os-schools-requests/issues?q=label%3Ashare-request).

## Description

This repo contains code to test the end-to-end process with real data.

(No real data will be stored in this repo, or any other research repo!)

## Instructions to run this code

To run this code, install [uv](https://docs.astral.sh/uv/guides/tools/), and run:

    uv run analysis/01_count_rows.py
