# Recommended reading

Papers your library cites repeatedly but that you have not read.
Generated from 61 papers; starred papers count treble.

## ESSENTIAL · DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning

- arXiv: [2501.12948](https://arxiv.org/abs/2501.12948)
-  DeepSeek-AI, Daya Guo, Dejian Yang, Haowei Zhang et al. · 2025
- cited by **23** of your papers
- The R1 paper is the primary source for RLVR reasoning that 23 of your papers build on; read the original, not just citations.

## ESSENTIAL · Monitoring Reasoning Models for Misbehavior and the Risks of Promoting Obfuscation

- arXiv: [2503.11926](https://arxiv.org/abs/2503.11926)
- Bowen Baker, Joost Huizinga, Leo Gao, Zehao Dou et al. · 2025
- cited by **19** of your papers · 6 citations overall
- Foundational source for the obfuscated-reward-hacking claim your Obfuscation Atlas and reward-hacking papers build on; gives the original CoT-monitorability-tax evidence, not restated elsewhere.

## ESSENTIAL · Alignment faking in large language models

- arXiv: [2412.14093](https://arxiv.org/abs/2412.14093)
- Ryan Greenblatt, Carson Denison, Benjamin Wright, Fabien Roger et al. · 2024
- cited by **11** of your papers · 22 citations overall
- The canonical demonstration that models strategically fake alignment during training — the behavioral phenomenon your reward-hacking, deception-probe, and CoT-faithfulness papers all build on.

## USEFUL · Value Leakage: An LLM's Answers Are Silently Shaped by Its Own Values

- arXiv: [2607.14345](https://arxiv.org/abs/2607.14345)
- Jan Betley, Johannes Treutlein, Jan Dubiński, Harry Mayne et al. · 2026
- suggested because you follow **Owain Evans**
- Extends your CoT-unfaithfulness cluster with a new hidden driver — latent values distorting answers on ostensibly value-neutral tasks — beyond Reasoning Theater's belief/CoT gap.

## USEFUL · Negation Neglect: When models fail to learn negations in training

- arXiv: [2605.13829](https://arxiv.org/abs/2605.13829)
- Harry Mayne, Lev McKinney, Jan Dubiński, Adam Karvonen et al. · 2026
- suggested because you follow **Owain Evans**
- A reversal-curse-style data-to-belief failure mode your library lacks: negated training statements ("never do X") may not become learned constraints, directly undermining spec-based safety alignment.

## USEFUL · The Consciousness Cluster: Emergent preferences of Models that Claim to be Conscious

- arXiv: [2604.13051](https://arxiv.org/abs/2604.13051)
- James Chua, Jan Betley, Samuel Marks, Owain Evans · 2026
- suggested because you follow **Owain Evans**
- Extends the emergent-misalignment persona story to a self-model axis — consciousness claims predicting correlated preferences — which none of your introspection or EM papers cover.

## USEFUL · DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models

- arXiv: [2402.03300](https://arxiv.org/abs/2402.03300)
- Zhihong Shao, Peiyi Wang, Qihao Zhu, Runxin Xu et al. · 2024
- cited by **12** of your papers · 78 citations overall
- Original GRPO derivation and unified RL-paradigm section underpin the RLVR training in your reward-hacking and reasoning papers; the math-corpus pipeline half is skippable.

## USEFUL · Universal and Transferable Adversarial Attacks on Aligned Language Models

- arXiv: [2307.15043](https://arxiv.org/abs/2307.15043)
- Andy Zou, Zifan Wang, Nicholas Carlini, Milad Nasr et al. · 2023
- cited by **11** of your papers · 190 citations overall
- GCG is the canonical jailbreak-optimization baseline your safety-alignment and misalignment papers cite, but it's attack methodology, not the internal-mechanism analysis your library centers on.

## MARGINAL · Qwen3 Technical Report

- arXiv: [2505.09388](https://arxiv.org/abs/2505.09388)
- An Yang, Anfeng Li, Baosong Yang, Beichen Zhang et al. · 2025
- cited by **15** of your papers · 98 citations overall
- It's the model card for the base models your library's papers train on; read only the RL/thinking-budget sections if you need setup details.

