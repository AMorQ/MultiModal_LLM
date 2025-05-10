# MultiModal Prompting

This repository explores innovative multimodal prompting strategies using `LLama 3.1/3.2` models. It introduces new capabilities such as tokenizer customization, API stack integration, and tool calling. The ultimate goal is to leverage these technologies to create a ballet assistant tailored for specific literature and expertise.

## Table of Contents

* [Highlights and Work in Progress](#highlights-and-work-in-progress)
* [Features](#features)
* [Setup and Installation](#setup-and-installation)
* [Usage](#usage)
* [Dependencies](#dependencies)
* [Future Enhancements](#future-enhancements)
* [Acknowledgments](#acknowledgments)
* [License](#license)

## Highlights and Work in Progress

### Build a Spanish Tokenizer
* Custom tokenizer for improved language understanding and generation in Spanish.

### Develop a Statistical Literature Review Tool
* Create an agent for statistical literature review and selection.
* Build a tutor for statistical concepts, supporting advanced academic workflows.

### Fine-Tune LLama Model
* Adapt the model to the specific needs of a ballet school and its literature.

## Features

### Multimodal Prompting
Utilize `LLama 3.1/3.2`'s advanced multimodal capabilities for creative applications.

### Custom Tool-Calling
Implement tool-calling strategies to enhance interactivity and functionality.

### Fine-Tuning for Domain-Specific Tasks
Train models on custom datasets for niche applications (e.g., ballet-specific content).

### Powered by Together.ai
Use `together.ai` endpoints for model integration and API calls.

## Setup and Installation

### Prerequisites

* Python 3.8 or newer.
* A package manager like `pip` or `conda`.
* Access to the `Together.ai` API.

### Installation Steps

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/AMorQ/MultiModal_LLM.git](https://github.com/AMorQ/MultiModal_LLM.git)
    cd MultiModal_LLM
    ```
2.  **Create and activate the environment:**
    ```bash
    conda env create -f environment.yaml
    conda activate multimodal_env
    ```
3.  **Install additional requirements (if needed):**
    ```bash
    pip install -r requirements.txt
    ```

## Usage

### Exploring Notebooks
Open the Jupyter notebooks (`.ipynb`) in the repository to explore multimodal prompting experiments.

### Fine-Tuning
Use the scripts provided to fine-tune the `LLama` model with your specific dataset (e.g., ballet school literature).

### Custom Tokenizer
Experiment with the Spanish tokenizer to enhance language-specific tasks.

### Tool Calling
Test and develop the statistical literature review functionalities and other agent-based tools.

## Dependencies

The repository relies on the following key libraries and tools:

* `LLama 3.1/3.2` Models
* `Together.ai` API
* Python Libraries:
    * `TensorFlow`
    * `NumPy`
    * `Pandas`
* Jupyter Notebooks

Refer to the `environment.yaml` or `requirements.txt` for a full list of dependencies.

## Future Enhancements

* Expand the ballet assistant to include interactive choreography suggestions.
* Add support for additional languages in the tokenizer.
* Integrate GPT-based models for enhanced multimodal capabilities.
* Publish statistical literature review tools as standalone utilities.

## Acknowledgments

Special thanks to `Together.ai` for providing endpoints for `LLama` models and enabling advanced experimentation in this project.
