# Mind-uploading

This project aims to create a digital copy of my mind by combining computing technology, especially artificial neural networks, with natural language datasets such as emails, text messages, diary entries, and voice recordings.

Below are Python Notebooks that process these datasets and use them as source material and training or fine-tuning data for OpenAI's Large Language Models.

# Jupyter Notebook Files in this Repository

## Raw data processing

### [Gmail_Mbox_to_TXT_JSON.ipynb](https://github.com/isaac-mackey/mind-uploading/blob/main/Gmail_Mbox_to_TXT_JSON.ipynb)

- **Description:** A Jupyter Notebook for exporting Gmail Mbox files and converting them to TXT and JSON formats.

### [SMS_XML_to_TXT_CSV_JSON.ipynb](https://github.com/isaac-mackey/mind-uploading/blob/main/SMS_XML_to_TXT_CSV_JSON.ipynb)

- **Description:** A Jupyter Notebook for converting SMS XML files to TXT, CSV, and JSON formats.

### [Audio_Transcription_Timestamps.ipynb](https://github.com/isaac-mackey/mind-uploading/blob/main/Audio_Transcription_Timestamps.ipynb)

- **Description:** A Jupyter Notebook for transcribing audio files and filtering audio and transcripts for specific content.

</br>

## Large Language Model Conversation with OpenAI's API 

### [OpenAI_API_Role_System_User_Assistant_Fine_Tuning_GPT3_5Turbo.ipynb](https://github.com/isaac-mackey/mind-uploading/blob/main/OpenAI_API_Role_System_User_Assistant_Fine_Tuning_GPT3_5Turbo.ipynb)

- **Description:** A Jupyter Notebook for fine-tuning a GPT-3.5 Turbo model with OpenAI's API using the role-based system/user/assistant format.

### [Completion_Mode_with OpenAI_API.ipynb](https://github.com/isaac-mackey/mind-uploading/blob/main/IsaacBot_SMS_Completion_Mode_GPT3_5Turbo.ipynb)

- **Description:** A Jupyter Notebook implementing a conversation using a fine-tuned GPT-3.5 Turbo model.

</br>

## Labeling Datasets with OpenAI's API

### [SMS_Labeling.ipynb](https://github.com/isaac-mackey/mind-uploading/blob/main/SMS_Labeling.ipynb)

- **Description:** A Jupyter Notebook for labeling SMS (Short Message Service) conversations.

### [Journal_Labeling.ipynb](https://github.com/isaac-mackey/mind-uploading/blob/main/Journal_Labeling.ipynb)

- **Description:** A Jupyter Notebook for labeling journal entries.

</br>

## Personality Trait Evaluation and Autobiographical Recall

### [Personality_Factors_Questionaire.ipynb](https://github.com/isaac-mackey/mind-uploading/blob/main/16_Personality_Factors_Questionaire.ipynb)

- **Description:** A Jupyter Notebook for conducting a questionnaire related to the 16 Personality Factors model on a Large Language Model.

### [Autobiographical_Prompts.ipynb](https://github.com/isaac-mackey/mind-uploading/blob/main/Autobiographical_Prompts.ipynb)

- **Description:** A Jupyter Notebook containing prompts for autobiographical writing.
