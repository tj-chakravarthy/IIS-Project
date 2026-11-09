# IIS-Project

Final project for Intelligent Interactive Systems, Uppsala University, HT 2026.
A Furhat virtual robot that detects the user's affective state from a webcam and
adapts its dialogue in response.

Team: Tejas Chakravarthy, Ahmad Sabbah, Tijn Veldwijk, Koen Veldhorst.

## Layout

- `perception/` — webcam input and affective state detection (own trained ML model)
- `interaction/` — Furhat dialogue, takes affective state and user speech
- `data/` — datasets, not tracked (e.g. DiffusionFER)
- `models/` — trained weights, not tracked

## Setup

```
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```
