# Capstone AI Data Set for Fine-Tuning Model

## Project Overview

This repository contains the dataset for the Capstone AI project aimed at fine-tuning a model to modify lesson content for students with learning disabilities. The fine-tuned model is designed to provide new or modified lesson content, specify modifications made for each diagnosis, and include research references in APA format. The goal is to enhance inclusivity and provide better educational resources for students with various learning disabilities.

## Purpose

The justification for using a fine-tuned model over a general ChatGPT model is to ensure output quality by controlling the format. This project aims to create a fine-tuned model that can utilize research-based strategies and diagnoses to effectively modify or create lesson content, achieving adapted lesson content for inclusive education.

## Repository Structure

├── Resources
│ ├── 50_elementary_school_learning_topics.txt
│ ├── 50_learning_disorders_combinations.txt
├── data_set.json
├── sample.json
├── README.md
└── LICENSE

### Resources Directory

- **50_elementary_school_learning_topics.txt**: A list of 50 different learning topics for elementary school students.
- **50_learning_disorders_combinations.txt**: A list of 50 combinations of learning disorders.

### Data Files

- **data_set.json**: Full dataset of 50 messages for the fine-tuning model, containing the modified lesson content, specific modifications for each diagnosis, and APA references.
- **sample.json**: Sample message body format for the fine-tuning model.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

