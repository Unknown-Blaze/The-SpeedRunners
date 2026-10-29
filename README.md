# The-SpeedRunners

Fitness tracker challenge from a MATLAB hackathon (2024): count steps and classify activity from phone sensor logs in MATLAB.

[![MATLAB](https://img.shields.io/badge/MATLAB-Online%20%26%20Mobile-0076A8?style=flat-square&logo=mathworks&logoColor=white)](https://www.mathworks.com/products/matlab-online.html)
![Live Script](https://img.shields.io/badge/Live%20Script-.mlx-E16737?style=flat-square)
![Hackathon](https://img.shields.io/badge/Hackathon-MATLAB%20fitness%20tracker-555555?style=flat-square)

<img src="Hackathons%20Banner.jpg" alt="MATLAB hackathon banner" width="100%">

## What it does

The challenge was to build a fitness tracker from data collected with MATLAB Mobile: GPS position, acceleration and timestamps logged on a phone. The example model in `ExampleModel.mlx` turns latitude and longitude into distance travelled along the path, divides by stride length to count steps, plots the route, and classifies activity from the acceleration logs. This repository contains the MathWorks starter kit for the challenge (instructions, rubric, example model and sample data, from [mathworks/matlab-mobile-fitness-tracker](https://github.com/mathworks/matlab-mobile-fitness-tracker)).

## Tech

MATLAB Online, MATLAB Mobile sensor logging, MATLAB Live Scripts.

## Run

Open `ExampleModel.mlx` in MATLAB or MATLAB Online with `ExampleData.mat`, `ActivityLogs.mat` and `timeElapsed.m` in the same folder, then run the sections in order. Or open it directly:

[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Unknown-Blaze/The-SpeedRunners&file=ExampleModel.mlx)

| File | Holds |
|---|---|
| [`Instructions.pdf`](Instructions.pdf) | Step-by-step guide to collecting data with MATLAB Mobile and building the tracker |
| [`GradingRubric.docx`](GradingRubric.docx) | The judges' rubric |
| [`ExampleModel.mlx`](ExampleModel.mlx) | Example model: step counting, graphics, activity classification |
| [`ExampleData.mat`](ExampleData.mat), [`ActivityLogs.mat`](ActivityLogs.mat) | Sample sensor data |
| [`timeElapsed.m`](timeElapsed.m) | Helper: datetime array to seconds since the first sample |

## Team

MatLab Hackathon Project (Fitness Tracker) by dEEEvelopers
