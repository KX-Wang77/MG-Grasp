# MG-Grasp: **Metric-Scale Geometric 6-DoF Grasping Framework with Sparse RGB Observations**

![video_pipe](static/videos/video_pipe.gif)

## Introduction

MG-Grasp is a depth-free 6-DoF robotic grasping framework designed for sparse RGB observations. Instead of relying on depth sensors, it reconstructs metric-scale and multi-view consistent geometry from RGB images and generates reliable grasp poses for robotic manipulation.

This repository hosts the official project page and related media assets for MG-Grasp.

## Overview

MG-Grasp connects sparse multi-view RGB perception and robotic grasp generation in a unified pipeline. The framework includes metric-scale recovery, multi-view refinement, and grasp-oriented geometric fusion, enabling robust RGB-only 6-DoF grasping in both benchmark and real-world settings.

## Highlights

- RGB-only 6-DoF grasping without depth input
- Metric-scale geometric reconstruction from sparse RGB views
- Multi-view consistent refinement for grasp-oriented geometry
- Real-world robotic grasping demonstrations

## Project Page Contents

The project page includes:

- project overview
- method description
- benchmark summary
- 6-DoF pose generation examples
- real-world robot experiments
- BibTeX citation

## Media Preview

This repository includes the following visual materials used in the project page:

### Teaser / Pipeline Overview
- `static/videos/video_pipe.gif`

### 6-DoF Pose Generation
![grasp_0100](static/videos/grasp_0100.gif)



<video src="static/videos/Scene_01.mp4" controls=""></video>

### Real-World Workflow

- `static/videos/video_realpipe.gif`

### Real-World Robot Experiments
- `static/videos/Scene_01.mp4`
- `static/videos/Scene_02.mp4`
- `static/videos/Scene_03.mp4`
- `static/videos/Scene_04.mp4`

## Repository Structure

```text
.
├── index.html
├── README.md
└── static/
    ├── css/
    ├── js/
    ├── images/
    ├── pdfs/
    └── videos/