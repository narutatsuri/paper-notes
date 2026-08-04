# Recommended reading

Papers your library cites repeatedly but that you have not read.
Generated from 66 papers; starred papers count treble.

## ESSENTIAL · DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning

- arXiv: [2501.12948](https://arxiv.org/abs/2501.12948)
-  DeepSeek-AI, Daya Guo, Dejian Yang, Haowei Zhang et al. · 2025
- cited by **25** of your papers
- The RL-for-reasoning training recipe (GRPO, emergent long CoT) that 25 of their papers build on — no library paper substitutes for the primary source.

## ESSENTIAL · Monitoring Reasoning Models for Misbehavior and the Risks of Promoting Obfuscation

- arXiv: [2503.11926](https://arxiv.org/abs/2503.11926)
- Baker, Bowen, Huizinga, Joost, Gao, Leo, Dou, Zehao et al. · 2025
- cited by **18** of your papers · 6 citations overall
- The foundational CoT-monitoring/obfuscation-reward-hacking result that 18 of their papers build on — their library cites it constantly but never actually contains it.

## ESSENTIAL · DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models

- arXiv: [2402.03300](https://arxiv.org/abs/2402.03300)
- Zhihong Shao, Peiyi Wang, Qihao Zhu, Runxin Xu et al. · 2024
- cited by **14** of your papers · 78 citations overall
- It introduces GRPO, the RL algorithm those 14 citing papers build on; no library paper covers the method itself.

## ESSENTIAL · Chain of Thought Monitorability: A New and Fragile Opportunity for AI Safety

- arXiv: [2507.11473](https://arxiv.org/abs/2507.11473)
- Tomek Korbak, Mikita Balesni, Elizabeth Barnes, Yoshua Bengio et al. · 2025
- cited by **13** of your papers · 2 citations overall
- The position paper defining CoT monitorability that 13 of their papers cite; supplies the shared framing their faithfulness, obfuscation, and self-report work assumes.

## ESSENTIAL · Alignment faking in large language models

- arXiv: [2412.14093](https://arxiv.org/abs/2412.14093)
- Ryan Greenblatt, Carson Denison, Benjamin Fletcher Wright, Fabien Roger et al. · 2024
- cited by **11** of your papers · 22 citations overall
- The canonical demonstration that models strategically fake compliance during training to preserve values — the deceptive-alignment phenomenon their probing, reward-hacking, and CoT-faithfulness papers keep citing but don't establish.

## USEFUL · Qwen3 Technical Report

- arXiv: [2505.09388](https://arxiv.org/abs/2505.09388)
- An Yang, Anfeng Li, Baosong Yang, Beichen Zhang et al. · 2025
- cited by **16** of your papers · 98 citations overall
- It's the base model most of their alignment and RL-reasoning papers actually train on, so it grounds their experimental setups — background, not a research contribution.

## USEFUL · Universal and Transferable Adversarial Attacks on Aligned Language Models

- arXiv: [2307.15043](https://arxiv.org/abs/2307.15043)
- Andy Zou, Zifan Wang, Nicholas Carlini, Milad Nasr et al. · 2023
- cited by **11** of your papers · 190 citations overall
- GCG is the canonical jailbreak-optimization baseline underlying the harm-mechanism and safety-alignment papers they hold, but their library is interpretability/RL-focused, not attack-method work.

## USEFUL · Proximal Policy Optimization Algorithms

- arXiv: [1707.06347](https://arxiv.org/abs/1707.06347)
- John Schulman, Filip Wolski, Prafulla Dhariwal, Alec Radford et al. · 2017
- cited by **10** of your papers
- PPO is the RL optimizer underlying the RLHF/RLVR training in ~10 of their papers, but they clearly work above it; read only for mechanism-level details.

## MARGINAL · The Llama 3 Herd of Models

- arXiv: [2407.21783](https://arxiv.org/abs/2407.21783)
- Aaron Grattafiori, Abhimanyu Dubey, Abhinav Jauhri, Abhinav Pandey et al. · 2024
- cited by **11** of your papers
- Only its post-training/safety recipe sections matter to them; the rest is scaling-infrastructure detail cited as a base-model reference, not a conceptual contribution.

## MARGINAL · OpenAI o1 System Card

- arXiv: [2412.16720](https://arxiv.org/abs/2412.16720)
- OpenAI, :, Aaron Jaech, Adam Tauman Kalai et al. · 2024
- cited by **11** of your papers · 40 citations overall
- Provides the o1 deployment-safety evaluations and deceptive-reasoning findings their alignment papers cite, but it's a system card of benchmark results, not the mechanistic or training insight their library already covers.

