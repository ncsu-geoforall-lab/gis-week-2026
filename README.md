# Geospatial Modeling, Machine Learning, and an LLM Walk into a Bar: Mapping Stream Banks from Lidar

Materials for the GIS Week 2026 workshop.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ncsu-geoforall-lab/gis-week-2026/blob/main/stream_banks_workshop_GeoAI.ipynb)

## About the workshop

In this hands-on workshop we use one small geospatial problem, finding the edges of a stream channel in a
high-resolution lidar terrain model, to explore how classic geospatial modeling, machine learning, and
generative AI fit together. Working with a stream in nearby Chatham County, we build the workflow with terrain
analysis, flow routing, and least-cost paths, then use its results to train a random forest and look at whether
it can improve on them. Along the way, we try out Gemini, the LLM built into Colab, on parts of the workflow
and see what it is good for. Everything runs in Google Colab with GRASS and Python. Some familiarity with
Python is helpful but not required.

## Running the notebook

Click the **Open in Colab** button above to open the workshop notebook. Some of its cells are left for you to
fill in with Gemini; if you get stuck, the complete notebook listed under [Contents](#contents) has the
answers. You need a Google account and nothing else.

The first cells install [GRASS](https://grass.osgeo.org/) from conda-forge. This takes a few minutes and
restarts the Colab runtime once. Colab will report that the session crashed, which is expected. Wait for it to
reconnect and continue with the next cell.

## Contents

| File | Description |
| --- | --- |
| [`stream_banks_workshop_GeoAI.ipynb`](stream_banks_workshop_GeoAI.ipynb) | Workshop notebook. Some cells are left out for you to fill in with Gemini. |
| [`stream_banks_workshop.ipynb`](stream_banks_workshop.ipynb) | Complete notebook with all the cells filled in, for reference. [Open in Colab](https://colab.research.google.com/github/ncsu-geoforall-lab/gis-week-2026/blob/main/stream_banks_workshop.ipynb) |
