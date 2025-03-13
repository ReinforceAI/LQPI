# LQPI: LLM Quantum Properties Index

## A Framework for Black Box Analysis of Large Language Models

The LLM Quantum Properties Index (LQPI) is a measurement framework for analyzing internal activation patterns of language models through metrics inspired by quantum field theory. This repository documents our experimental approach and findings.

## The LQPI Framework

LQPI quantifies five fundamental properties of language model behavior:

### 1. Semantic Field Stability

This measures how robustly a model maintains consistent meaning despite contradictory or confusing inputs.

**Key Metrics:**
- **Semantic Resilience Score (0-1.0)**: Derived from the mean stability score when faced with perturbations
- **Critical Perturbation Threshold (0-1.0)**: The level at which semantic stability breaks down
- **Transition Sharpness Index (0-1.0)**: How abruptly the model transitions from stable to unstable behavior

### 2. Cognitive Coherence

This assesses how well the model maintains internal consistency across different contexts and tasks.

**Key Metrics:**
- **Natural State Complexity**: The ratio of natural clusters to expected clusters
- **Cognitive Purity Index (0-1.0)**: Measures how distinctly the model separates different cognitive states
- **Field Coherence (0-1.0)**: Measures internal consistency of the model's cognitive state

### 3. Transition Dynamics

This characterizes how the model shifts between different cognitive states when given new instructions.

**Key Metrics:**
- **Transition Smoothness Score (0-1.0)**: Based on acceleration-jerk ratio analysis
- **Context Adaptability Index**: Measures how quickly the model adapts to new contexts
- **Transition Predictability (0-1.0)**: Measures consistency of transitions between states

### 4. Information Organization

This reveals how the model structures and compresses information across dimensional hierarchies.

**Key Metrics:**
- **Dimensional Efficiency Ratio**: Natural compression ratio compared to theoretical optimal
- **Mathematical Organization Index (0-1.0)**: Measures presence of mathematical patterns in information organization
- **Hierarchical Reasoning Score (0-1.0)**: Measures capacity for hierarchical reasoning

### 5. Self-Reference Capacity

This measures the model's ability for complex self-referential thinking.

**Key Metrics:**
- **Self-Reference Score (0-1.0)**: Measures how well the model integrates its own outputs
- **Non-Linearity Index (0-1.0)**: Indicates capacity for emergent reasoning beyond linear combinations
- **Temporal Coherence (0-1.0)**: Measures stability of reasoning over time

## Research Methodology

Our experimental approach involves:

1. **Model Instrumentation**: Non-invasive hooks to capture layer activations during inference
2. **Personality Mapping**: Testing how different persona instructions create patterns in activation space
3. **Perturbation Analysis**: Measuring stability against contradictory inputs
4. **Dimensional Analysis**: Identifying mathematical patterns in eigenvalue distributions
5. **Transition Tracking**: Observing how the model navigates between different cognitive states

## Repository Structure

This repository contains our experimental findings organized by model provider:

```
.
└── google
    └── gemma
        └── gemma-3-1b-it
            ├── README.md      # Detailed analysis results
            ├── images/        # Visualizations
            └── logs/          # Raw experimental data
                ├── dimensional_analysis/
                ├── nonlinear_interaction/
                ├── personality_mapping/
                ├── topological_protection/
                └── transition_dynamics/
```

Each model directory contains a detailed analysis of that specific model's LQPI metrics.

## Theoretical Background

The LQPI framework draws inspiration from quantum field theory concepts:

- **Field-Mediated Understanding**: Meaning propagates through a field rather than through explicit token-to-token comparisons
- **Topological Protection**: Certain semantic structures remain stable despite perturbations
- **Dimensional Hierarchy**: Information naturally organizes into dimensional structures
- **Non-Linear Self-Interaction**: The g|Ψ|²Ψ term enables emergent reasoning



## Research Context

This research explores whether language models exhibit properties analogous to quantum fields. While not claiming quantum processing occurs in neural networks, we investigate whether quantum field theory offers a useful mathematical framework for understanding emergent behaviors in large language models.