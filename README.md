# Processes on Networks

An interactive educational website on **processes unfolding on networks**, developed for the course **Networks and Complex Systems** by **Cristian Candia, Ph.D.** and published through **CRiSS Lab**.

The site connects network structure with dynamics through short theoretical sections and interactive simulations. It focuses on how diffusion, epidemics, intervention strategies, and temporal constraints change the interpretation of node importance and network behavior.

## Overview

This project is a static bilingual website designed as a teaching resource for graduate-level network science. It introduces the main intuition behind epidemic and diffusion processes on graphs, while keeping the presentation visual, interactive, and accessible.

The website is organized into five main sections:

- **Models**: conceptual comparison between **SIS** and **SIR**
- **Threshold**: epidemic threshold and structural approximations
- **SIR Simulation**: trajectory-based and Monte Carlo exploration
- **Intervention**: comparison of node-removal or immunization strategies
- **Temporal**: differences between temporal networks and aggregated networks

## Educational Goal

The goal of the site is to help students understand a central idea in network science:

> The relevance of a node depends on the process taking place on the network, the time horizon, and the intervention objective.

Rather than presenting a single “best” centrality or a universal strategy, the resource shows why conclusions depend on the dynamics being modeled.

## Features

- Interactive simulations in vanilla JavaScript
- Explanatory cards combining theory and intuition
- Spanish and English entry pages
- Responsive layout for desktop and mobile
- Static deployment with no build step
- Social sharing metadata and preview assets
- Favicon and web manifest support

## Topics Covered

- SIS and SIR dynamics on networks
- Local transition rules and state evolution
- Epidemic threshold intuition
- Structural comparison across graph models
- SIR outbreak trajectories
- Monte Carlo estimation
- Node intervention strategies
- Temporal reachability vs aggregated connectivity

## Tech Stack

This site is built as a static web resource using:

- **HTML**
- **CSS**
- **Vanilla JavaScript**
- **Canvas** for interactive visualizations
- **Google Fonts** for typography

## Project Structure

```text
procesos_en_redes/
├── index.html
├── index-en.html
├── site.webmanifest
├── site-en.webmanifest
├── assets/
│   ├── apple-touch-icon.png
│   ├── favicon-16.png
│   ├── favicon-32.png
│   ├── favicon-square.png
│   ├── favicon.png
│   ├── share-social.jpg
│   └── share.png
└── README.md
```

## Credits

Created as a teaching resource for the course **Networks and Complex Systems**, by **Cristian Candia, Ph.D.** and **CRiSS Lab**.
