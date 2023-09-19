# PromptEngineering
This project consists of various use cases of prompt engineering. Each file has their own use case explaations for users to contribute and use. 
We also suggest you to check [DeepLearning.ai](https://deeplearning.ai) "ChatGPT Prompt Engineering for Developers" training.

## Setup

1) Install the latest [Python](python.org/) version 
2) Install the OpenAI Python library, run the below command in your terminal:
```sh
!pip install openai
```
3) Set OPENAI_API_KEY variable with your OpenAI account key, which is available on the [OpenAI Account Page](https://platform.openai.com/account/api-keys)
3.1) You can either set it as the OPENAI_API_KEY environment variable before using the library as 
```sh
!export OPENAI_API_KEY='sk-...'
```
3.2) Or, set openai.api_key inside the python file to its value:
```sh
openai.api_key = "sk-..."
```
4) Clone the respository and run each file. Feel free to edit ad iterate the prompts

## List of Files inside the projects
| File Name | Objective | README |
| ------ | ------ | ------ |
| CustomerServiceAIAssistant.py | TBD | [plugins/dropbox/README.md][PlDb] |
| TourPlanningAIAssistant.py | TBD | [plugins/dropbox/README.md][PlDb] |
