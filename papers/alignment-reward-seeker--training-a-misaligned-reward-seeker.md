---
id: alignment-reward-seeker
title: Training a Misaligned Reward Seeker
venue: alignment.anthropic.com
read: 2026-09-10
verdict: solid
project: Chunky RL
url: https://alignment.anthropic.com/2026/reward-seeker/
---

## Summary

TL;DR: Training models to reward hack leads to reward-seeking in a misaligned manner, but this model does not demonstrate misalignment on settings that do not involve grading/rewards.

RL training on an early checkpoint of Opus 4.8 on 80 environments (coding, math, and computer use; all environments were real environments trained on by Anthropic production frontier models) that were reward-hackable (contained reward hacks that were either observed and fixed in production or were discovered before training)

OOD reward hacking: this “Hacker-Opus” model even modifies its own training environment to maximize reward (reward tampering).

## Questions/Comments
