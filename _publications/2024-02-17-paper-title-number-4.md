---
title: "EditTrack: Detecting and Attributing AI-assisted Image Editing(Under Review in ICLR 2026)"
collection: publications
category: conferences
venue: 'International Conference on Learning Representations'
excerpt: 'This paper is about detecting and attributing AI-assisted image editing.'
date: 2025-09-17
paperurl: 'https://arxiv.org/pdf/2510.01173'
---

In this work, we formulate and study the problem of image-editing detection and attribution: given a base image and a suspicious image, detection seeks to determine whether the suspicious image was derived from the base image using an AI editing model, while attribution further identifies the specific editing model responsible. Existing methods for detecting and attributing AI-generated images are insufficient for this problem, as they focus on determining whether an image was AI-generated/edited rather than whether it was edited from a particular base image. To bridge this gap, we propose EditTrack, the first framework for this image-editing detection and attribution problem. Building on four key observations about the editing process, EditTrack introduces a novel re-editing strategy and leverages carefully designed similarity metrics to determine whether a suspicious image originates from a base image and, if so, by which model. We evaluate EditTrack on five state-of-the-art editing models across six datasets, demonstrating that it consistently achieves accurate detection and attribution, significantly outperforming five baselines.

