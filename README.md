# Mind-uploading

This project combines computing technology with natural language datasets such as emails, text messages, diary entries, and voice recordings. The intent is to create a digital copy of my mind.

First, I export datasets from native application formats (e.g., Gmail mbox, Android SMS xml) into stable forms (e.g., txt files) that may outlive the application and allow further processing. Next, I use basic data mining programs as well as processing by large language models to identify recurring topics and communication patterns. Then, I replicate my linguistic patterns by fine-tuning large language models to these datasets.

Below are some Python Notebooks to perform the tasks described above.

## Raw data processing

### [Gmail_Mbox_to_TXT_JSON.ipynb](https://github.com/isaac-mackey/mind-uploading/blob/main/Gmail_Mbox_to_TXT_JSON.ipynb)

- **Description:** A Jupyter Notebook for exporting Gmail Mbox files and converting them to TXT and JSON formats.

### [SMS_XML_to_TXT_CSV_JSON.ipynb](https://github.com/isaac-mackey/mind-uploading/blob/main/SMS_XML_to_TXT_CSV_JSON.ipynb)

- **Description:** A Jupyter Notebook for converting SMS XML files to TXT, CSV, and JSON formats.

### [Audio_to_Transcription_with_Timestamps.ipynb](https://github.com/isaac-mackey/mind-uploading/blob/main/Audio_Transcription_Timestamps.ipynb)

- **Description:** A Jupyter Notebook for transcribing audio files and filtering audio and transcripts for specific content.

</br>

## Labeling Personal Datasets with OpenAI's API

### [SMS_Labeling.ipynb](https://github.com/isaac-mackey/mind-uploading/blob/main/SMS_Labeling.ipynb)

- **Description:** A Jupyter Notebook for labeling SMS (Short Message Service) conversations with OpenAI's API.

### [Journal_Labeling.ipynb](https://github.com/isaac-mackey/mind-uploading/blob/main/Journal_Labeling.ipynb)

- **Description:** A Jupyter Notebook for labeling journal entries with OpenAI's API.

</br>

## Tuning Large Language Models with Personal Datasets and OpenAI's API 

### [OpenAI_API_Role_System_User_Assistant_Fine_Tuning_GPT3_5Turbo.ipynb](https://github.com/isaac-mackey/mind-uploading/blob/main/OpenAI_API_Role_System_User_Assistant_Fine_Tuning_GPT3_5Turbo.ipynb)

- **Description:** A Jupyter Notebook for fine-tuning a GPT-3.5 Turbo model with OpenAI's API using the role-based system/user/assistant format.

### [Completion_Mode_with OpenAI_API.ipynb](https://github.com/isaac-mackey/mind-uploading/blob/main/IsaacBot_SMS_Completion_Mode_GPT3_5Turbo.ipynb)

- **Description:** A Jupyter Notebook implementing conversations with a fine-tuned GPT-3.5 Turbo model.

</br>

## Personality Trait Evaluation and Autobiographical Recall

### [Personality_Factors_Questionaire.ipynb](https://github.com/isaac-mackey/mind-uploading/blob/main/16_Personality_Factors_Questionaire.ipynb)

- **Description:** A Jupyter Notebook for conducting a questionnaire related to the 16 Personality Factors model on a Large Language Model.

### [Autobiographical_Prompts.ipynb](https://github.com/isaac-mackey/mind-uploading/blob/main/Autobiographical_Prompts.ipynb)

- **Description:** A Jupyter Notebook containing prompts for autobiographical writing.
