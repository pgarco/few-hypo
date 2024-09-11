# Few Hypocrites :speaking_head: :earth_africa:
Detecting Hypocrisy Accusations in Online Sustainability Debates, Subtype Definitions & Few-Shot Learning

## Abstract

The climate crisis is a significant issue in online discussions, where hypocrisy accusations often play a crucial rhetorical role. Despite this, **hypocrisy accusation detection** is an underexplored tool in large-scale text analysis, typically treated as a smaller subtask of fallacious argument detection. This paper redefines hypocrisy accusation detection as a standalone task within NLP, identifying distinct subtypes of hypocrisy accusations. The **Climate Hypocrisy Accusation Corpus (CHAC)**, containing 420 Reddit comments from climate debates, is annotated by experts to distinguish between personal and political hypocrisy accusations. We evaluate the performance of few-shot in-context learning using 6 shots and 3 instruction-tuned Large Language Models (LLMs) in detecting hypocrisy accusations within this dataset. The results highlight that GPT-4 and Llama-3 models are particularly effective in detecting hypocrisy accusations, achieving an F1 score of 0.68, compared to a previous F1 of 0.44. However, the models struggle more with identifying political hypocrisy accusations as opposed to personal moral hypocrisy, underscoring the importance of context in understanding such a complex semantic concept. This study advances the field of hypocrisy detection and contributes valuable insights into the discourse on climate change, laying the groundwork for large-scale analysis of hypocrisy accusations in online climate debates.

## Repository Contents

This repository contains the following files and resources related to our study on detecting hypocrisy accusations in online sustainability debates:

## Labels:

- No acc  - 0
- PMH     - 1
- PH      - 2
- Neither - 3

## Folders: 

### Analysis notebooks 
- **error-analysis.ipynb**: Jupyter Notebook to run few-shot learning experiment 
- **llm-prompt.ipynb**: Jupyter Notebook to run error analysis

### Data files
- **chac_data.csv**: The **Climate Hypocrisy Accusation Corpus (CHAC)**, a corpus of 420 expert-annotated Reddit comments from climate debates.
- **few_hypo_llm_outputs.csv**: This file contains the results of our few-shot learning experiments with different LLMs for hypocrisy accusation detection.

## Usage

To gain access to the full dataset, please refer to the Hugging Face [https://huggingface.co/datasets/Myrthe/RedditEuropeanSustainabilityInitiatives] dataset and accept terms and conditions. Files in the github repository do not contain the original comment body to protect privacy, this can be accessed via comment_id that is available in the Hugging Face dataset. 

This repository is intended for researchers and practitioners interested in exploring hypocrisy accusation detection within online climate change debates. The provided datasets and experiment results can be used for further research, replication studies, or development of new models.

## Citation

If you use any part of this work, especially the OCHAC corpus or the few-shot learning results, please cite our paper as follows:

