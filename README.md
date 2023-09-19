# PromptEngineering
This project includes a multitude of minor ChatGPT application use cases. In each file, you can submit and utilize use case descriptions. We also suggest that you investigate the "ChatGPT Prompt Engineering for Developers" program by [DeepLearning.ai](https://deeplearning.ai).

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
