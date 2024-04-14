# Persian Token Analysis

This repository contains a Python script for analyzing tokenizers of various large language models to measure their exposure to Persian data. The script counts tokens containing Persian characters, providing insights into the models' proficiency in processing Persian language.

## How it Works

The provided Python script downloads tokenizers for a list of pre-trained language models and calculates the percentage of tokens that contain at least one Persian character. This metric offers a glimpse into the models' familiarity with Persian language data.

## Results

The following table displays the percentage of tokens containing Persian characters for each model:

| Model Name                                      | Persian Tokens Percentage | Vocabulary Size |
|-------------------------------------------------|---------------------------|-----------------|
| mistralai/Mixtral-8x7B-Instruct-v0.1            | 0.225%                    | 32000           |
| mistralai/Mistral-7b-Instruct-v0.1              | 0.225%                    | 32000           |
| cohereForAI/aya-101                              | 9.279%                   | 250100          |
| databricks/dbrx-instruct                         | 0.0%                      | 100278          |
| CohereForAI/c4ai-command-r-plus                  | 0.0%                      | 255000          |
| Qwen/Qwen1.5-32B                                 | 0.0%                      | 151643          |
| HuggingFaceH4/zephyr-7b-beta                     | 0.225%                    | 32000           |
| tiiuae/falcon-180B-chat                          | 0.0%                      | 65024           |
| Nexusflow/Starling-LM-7B-beta                    | 0.225%                    | 32000           |
| Neurai/NeuraOrcaGemma7b                          | 8.288%                   | 256000          |
