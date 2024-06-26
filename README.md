# Mind-uploading

This project combines computing technology with personal natural language datasets such as emails, text messages, diary entries, and voice recordings.

Below are Python Notebooks for:
- exporting datasets from native application formats (e.g., Gmail mbox, Android SMS xml) into stable forms (e.g., txt files) that may outlive the application and allow further processing
- basic data mining and processing by large language models to identify recurring topics and communication patterns
- tuning large language models to these datasets
- prompting language models for personality and autobiographical information

## Dataset extraction

### [Gmail_Mbox_to_TXT_JSON.ipynb](https://github.com/isaac-mackey/mind-uploading/blob/main/Gmail_Mbox_to_TXT_JSON.ipynb)

- **Description:** A Python Notebook for exporting Gmail Mbox files and converting them to TXT and JSON formats.

### [SMS_XML_to_TXT_CSV_JSON.ipynb](https://github.com/isaac-mackey/mind-uploading/blob/main/SMS_XML_to_TXT_CSV_JSON.ipynb)

- **Description:** A Python Notebook for converting SMS XML files to TXT, CSV, and JSON formats.

### [Audio_to_Transcription_with_Timestamps.ipynb](https://github.com/isaac-mackey/mind-uploading/blob/main/Audio_Transcription_Timestamps.ipynb)

- **Description:** A Python Notebook for transcribing audio files and filtering audio and transcripts for specific content.

</br>

## Data Mining and Labeling

### [SMS_Labeling.ipynb](https://github.com/isaac-mackey/mind-uploading/blob/main/SMS_Labeling.ipynb)

- **Description:** A Python Notebook for labeling SMS (Short Message Service) conversations with OpenAI's API.

### [Journal_Labeling.ipynb](https://github.com/isaac-mackey/mind-uploading/blob/main/Journal_Labeling.ipynb)

- **Description:** A Python Notebook for labeling journal entries with OpenAI's API.

</br>

## Tuning Large Language Models with OpenAI's API 

### [OpenAI_API_Role_System_User_Assistant_Fine_Tuning_GPT3_5Turbo.ipynb](https://github.com/isaac-mackey/mind-uploading/blob/main/OpenAI_API_Role_System_User_Assistant_Fine_Tuning_GPT3_5Turbo.ipynb)

- **Description:** A Python Notebook for fine-tuning a GPT-3.5 Turbo model with OpenAI's API using the role-based system/user/assistant format.

### [Completion_Mode_with OpenAI_API.ipynb](https://github.com/isaac-mackey/mind-uploading/blob/main/IsaacBot_SMS_Completion_Mode_GPT3_5Turbo.ipynb)

- **Description:** A Python Notebook implementing conversations with a fine-tuned GPT-3.5 Turbo model.

</br>

## Prompts for Personality Trait Evaluation and Autobiographical Recall

### [Personality_Factors_Questionaire.ipynb](https://github.com/isaac-mackey/mind-uploading/blob/main/16_Personality_Factors_Questionaire.ipynb)

- **Description:** A Python Notebook for conducting a questionnaire related to the 16 Personality Factors model on a Large Language Model.

### [Autobiographical_Prompts.ipynb](https://github.com/isaac-mackey/mind-uploading/blob/main/Autobiographical_Prompts.ipynb)

- **Description:** A Python Notebook containing prompts for autobiographical writing.
