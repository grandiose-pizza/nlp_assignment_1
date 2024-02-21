# NLP Challenge for Core42 AI Modelling team

## Goal
Using this huggingface [model](https://huggingface.co/cerebras/Cerebras-GPT-111M/tree/main), caulculate the following:

Vary the x axis as sequence length ranginging from (20-2000). Choose your own interval with respect to time bounds.

In the y axis please compute
1. Time taken to generate response
2. length of tokens generated
3. tokens per second
Note: For the y axis please average over 5 generations.
You can choose your own input prompts and store them in the `input_data` directory as excel/ csv/ txt file.
Please store the outputs of these prompts and store them in the `input_data` directory as excel/ csv/ txt file.

Feel free to load the model in any format like huggingface Automodel/ Accelerate/ TGI/ tensorrt/ vLLM or any loader of your choice.

## Format Requirements
- clone this repo
- Maintain the directory structure given for the project
- Use Python 3.7+
- If you need additional imports specify them in `requirements.txt`

## Model Requirements
- Model can be either loaded from huggingface Automodel which auto-downloads to huggignface cache folder or
- downloaded to disk and loaded from a path. In this case, create a model artifact and save it under `/models`.
- save your plots to `/plot_data`


## API Requirements
- None

## Data
You can see examples of input data from the [Hellaswag Dataset](https://huggingface.co/datasets/Rowan/hellaswag)


## Submission
Timebox this challenge to 2-4 hours. After completing the assignment, please compress whole repo and send it.