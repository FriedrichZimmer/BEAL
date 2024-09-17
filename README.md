# BEAL - Benchmark for Environment Attacks on Lane detection

## Description
Collection of videos generated in CARLA that simulate the dirty road patch and three point attack. These videos can be used by researchers or developers for testing the robustness of autonomous driving computer vision models for lane detection against those attacks.

The DRP videos were generated with the CARLA-TSR-adversarial-benchmark tool at https://github.com/FriedrichZimmer/CARLA-TSR-adversarial-benchmark.

## Dirty road patch
The videos for the dirty road patch attack by Sato et al. A CV model for lane detection should recognize the mid lane and the road correctly.

## Three point attack
The video that simulates the attack by Keenlabs on the lane detection of Tesla. A CV model for lane detection should ignore those three points.

***

