# LLM Multiplication Capability Evaluation Framework

A comprehensive framework for evaluating and comparing the mathematical multiplication capabilities of various Large Language Models (LLMs) across different prompting strategies.

## Overview

This project provides a systematic way to evaluate how different LLMs perform on integer multiplication tasks, from single-digit to ten-digit numbers. It tests various prompting strategies to understand how different communication styles affect model performance.

## Features

- **Multiple Model Support**: Tests across major LLM providers including:
  - OpenAI (GPT-4, GPT-3.5 variants)
  - Anthropic (Claude 3.x series)
  - Google (Gemini series)
  - Meta (Llama series)
  - Amazon (Nova series)
  - And more

- **Diverse Prompting Strategies**:
  - Normal: Direct mathematical queries
  - Emotional: High-stress, urgent requests
  - Reasoning: Step-by-step calculation requests
  - Bullying: Negative reinforcement
  - Polite Request: Courteous, formal approach

- **Comprehensive Test Cases**:
  - Single-digit multiplication (0-9)
  - Two-digit multiplication
  - Three-digit multiplication
  - Up to ten-digit multiplication

- **Interactive Results Dashboard**:
  - Visual comparison of model performance
  - Detailed test case results
  - Pass/Fail statistics
  - Click-through details for each test case

## Setup

1. Install the required dependencies:
```bash
npm install promptfoo
```

2. Configure your API keys in the environment:
```bash
export OPENROUTER_API_KEY="your-api-key"
```

3. Run the evaluation:
```bash
npx promptfoo@latest eval
```

## Configuration

The evaluation is configured through `promptfooconfig.yaml`, where you can:
- Select which models to test
- Define different prompting strategies
- Configure test cases
- Set up assertions and validation rules

## Results

Results are displayed in an interactive HTML dashboard (`index.html`) that shows:
- Overall pass rates for each model
- Performance across different prompting strategies
- Detailed test case results
- Success/failure statistics

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built with [promptfoo](https://www.promptfoo.dev/)
- Results visualization powered by Bootstrap 5 