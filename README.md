# | NLP | PERF | DialogSum | Dialogue Summarize | 

## NLP (Language Natural Processing) and PERF (Parameter Efficient Fine-Tuning) for Dialogue Summarization

# <b>Introduction</b>

This project delves into the capabilities of LLM (Language Model) with a specific focus on leveraging PERF (Parameter Efficient Fine-Tuning) for enhancing dialogue summarization using the FLAN-T5 model.

Our goal is to enhance the quality of dialogue summarization by employing a comprehensive fine-tuning approach and evaluating the results using ROUGE metrics. Additionally, we will explore the advantages of Parameter Efficient Fine-Tuning (PEFT), demonstrating that its benefits outweigh any potential minor performance trade-offs.

 - NOTE: This is an example and we not using the entirety of the data used for PERF / LoRA.
 
## Objectives :
 - Train LLM for Dialogue Summarization.
 
 
 ## The DialogSum Dataset:
The [DialogSum Dataset](https://huggingface.co/datasets/knkarthick/dialogsum) DialogSum is a large-scale dialogue summarization dataset, consisting of 13,460 (Plus 100 holdout data for topic generation) dialogues with corresponding manually labeled summaries and topics.

## Project Workflow:

- **Setup**: Import necessary libraries and define project parameters.
- **Dataset Exploration**: Discovering DialogSum Dataset.
- **Test Model Zero Shot Inferencing**: Initially, test the FLAN-T5 model for zero-shot inferencing on dialogue summarization tasks to establish a baseline performance.
- **Dataset Preprocess Dialog and Summary**: Preprocess the dialog and its corresponding summary from the dataset to prepare for the train.
-  **Perform Parameter Efficient Fine-Tuning (PEFT)**: Implement Parameter Efficient Fine-Tuning (PEFT), a more efficient fine-tuning approach that can significantly reduce training time while maintaining performance.
-  **Evaluation**:
    - Perform human evaluation to gauge the model's output in terms of readability and coherence. This can involve annotators ranking generated summaries for quality.
    - Utilize ROUGE metrics to assess the quality of the generated summaries. ROUGE measures the overlap between generated summaries and human-written references.
 
[| View on Kaggle |](https://www.kaggle.com/code/yannicksteph/lnp-perf-dialogsum-dialogue-summarize/)
