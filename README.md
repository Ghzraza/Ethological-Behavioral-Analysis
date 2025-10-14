# Ethological-Behavioral-Analysis
Analysis of animal behavior in ethological environments 


Overview
This repository demonstrates automated behavioral tracking and analysis of animals in ethological environments. It provides a computational framework to simulate, track, and analyze positional and behavioral data, with methods applicable to a variety of neuroscience and ethology studies.

The repo includes:

Multi-animal trajectory simulation in 2D arenas

Behavioral metrics: distance traveled, speed, zone occupancy, time in proximity to other animals or objects

Visualizations: trajectories, heatmaps, speed over time

AI-based behavioral predictions: classify social interactions or exploratory behavior from positional features

Purpose
This project demonstrates method literacy in behavioral neuroscience: how to process and analyze animal movement data, extract meaningful metrics, and model behavior computationally.

It is designed to be generalizable across projects that involve:

Neurobehavioral studies: linking neural activity (Ca²⁺ imaging, electrophysiology) to behavior

Ethological research: social behavior, exploration, object interaction, anxiety tests

Computational neuroscience: simulating and analyzing temporal dynamics of behavior

Key Features

Simulation-based: Generate positional data for one or multiple animals in custom arenas

Behavioral metrics: Total distance, speed, time in defined zones, proximity to other animals

Visualization tools: Trajectories, positional heatmaps, velocity plots

Predictive modeling: AI-based classification of behaviors from positional features

Exportable datasets: Save all simulated positional and metric data for downstream analysis

Example Use Cases / Neuroscience Applications

Ethological behavior studies: Social interaction, exploration, anxiety-like behaviors

Neural-behavioral correlation: Integrate with Ca²⁺ imaging, electrophysiology, or optogenetic experiments

Behavioral modeling: Predict responses to stress, social cues, or pharmacological interventions

Tool development: Test tracking pipelines or behavior classification algorithms

Getting Started

Open the notebook in Google Colab or locally using Python 3.x.

Run the simulation cells to generate positional data for one or multiple animals.

Explore trajectories, heatmaps, and calculate behavioral metrics.

Optionally, run the AI-based behavior prediction section to classify social interactions or other behaviors.

Dependencies

numpy

pandas

matplotlib

seaborn

scikit-learn

Transferability

The framework is highly transferable across neuroscience and ethology projects:

Any study that requires tracking animal movement or behavior over time

Integrating positional data with neural recordings

Training AI models to classify or predict behavioral outcomes
