# Vocal Extraction Evaluation
![image](https://github.com/EngrIbrahimAdnan/VocalExtraction-Evaluation/assets/123921774/5f22713f-bd62-4b46-aa81-ed49426001f9)
## Overview

This repository provides a comprehensive evaluation of different methods for vocal extraction from music. The evaluated methods include Librosa, Spleeter, Audacity, and VocalRemover. The primary goal is to analyze the performance, technicality, and fine-tuning capabilities of each method to determine the most efficient tool for vocal and music extraction.

## Repository Structure

### Public Repository: VocalExtraction-Evaluation

This is the public repository that contains:

- The **Wiki** with detailed documentation on each method, including setup instructions and technical explanations.
- A **generic README** providing an overview and general information about the project.

### Private Repository: VocalExtraction-Evaluation_private

The [private repository](https://github.com/EngrIbrahimAdnan/VocalExtraction-Evaluation_private) contains:

- **Source code** for the evaluation scripts.
- **Sample project files** used in the evaluation.
- **Additional documentation** not included in the public wiki.

The private repository is added as a submodule in the public repository.

## How to Access the Private Repository

To gain access to the private repository (`VocalExtraction-Evaluation_private`), please get in touch to be added as a collaborator. Once granted access, you can view the full evaluation scripts and sample project files.

## How to Clone the Repository

To clone the public repository along with the private submodule, use the following commands:

```bash
git clone https://github.com/EngrIbrahimAdnan/VocalExtraction-Evaluation.git
cd VocalExtraction-Evaluation
git submodule init
git submodule update
```

## Methods Evaluated

1. **Librosa**: A Python library for analyzing audio and music.
2. **Spleeter**: A Python-written library with pre-trained models using TensorFlow.
3. **Audacity**: A general audio editor with a built-in vocal extraction function.
4. **VocalRemover**: An online application using AI for vocal and instrumental separation.

## Summary of Results

- **Extraction Performance**: Spleeter was found to be the most efficient tool for vocal and music extraction.
- **Technicality**: Spleeter is exceptionally easy to use, requiring minimal technical knowledge.
- **Fine-Tuning**: Spleeter allows model training for fine-tuning, providing extensive control over the extraction process.

For a detailed analysis and technical breakdown of each method, please refer to the [Wiki](https://github.com/EngrIbrahimAdnan/VocalExtraction-Evaluation/wiki).

## Contact

For any questions or to request access to the private repository, please contact iaa2132@columbia.edu.
