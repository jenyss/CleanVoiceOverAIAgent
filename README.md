# Clean Voice-Over AI Agent

This ReAct LangGraph Agent 𝗽𝗿𝗼𝗱𝘂𝗰𝗲𝘀 𝗮 𝘃𝗶𝗱𝗲𝗼 𝘄𝗶𝘁𝗵 𝗮 𝗰𝗹𝗲𝗮𝗻 𝘃𝗼𝗶𝗰𝗲-𝗼𝘃𝗲𝗿 𝗯𝘆 𝗿𝗲𝗽𝗹𝗮𝗰𝗶𝗻𝗴 𝘁𝗵𝗲 𝗼𝗿𝗶𝗴𝗶𝗻𝗮𝗹 𝗿𝗲𝗰𝗼𝗿𝗱𝗲𝗱 𝘃𝗼𝗶𝗰𝗲 𝘄𝗶𝘁𝗵 𝗮𝗻 𝗔𝗜-𝗴𝗲𝗻𝗲𝗿𝗮𝘁𝗲𝗱 𝗼𝗻𝗲.

If you have any questions or would like to collaborate, feel free to reach out to me on [LinkedIn](https://www.linkedin.com/in/jenya-stoeva-60477249/). You're more than welcome!

## 𝗔𝗴𝗲𝗻𝘁 𝗧𝗼𝗼𝗹𝘀
* ExtractAudio - FFmpeg
* TranscribeAudio (with timestamps) - OpenAI Whisper API
* CleanTranscript (with preserved timestamps) - OpenAI GPT-4o
* GenerateAIVoice - ElevenLabs
* RemoveOldVoice - FFmpeg
* MergeAudio - FFmpeg

## Intallation

<b>Prerequisites</b>

* Access to <b>JupyterLab, Google Colab</b>, or another interactive computing environment to run this Jupyter Notebook.

### Step 1: Clone the Repository

Clone this repository to your local machine:
```
git clone <REPOSITORY_URL>
cd <PROJECT_FOLDER>
```

### Step 2: Open Jupyter Notebook in JupyterLab

Ensure that ```<PROJECT_FOLDER>``` is accessible in JupyterLab by setting it as your working directory in JupyterLab.
 * In JupyterLab, use the "Open from Path" option to load ```CleanVoiceOverAIAgent.ipynb```.
 * Similarly, load ```.env``` and populate the variable keys with appropriate values.
 * The first cell in the Notebook installs the required libraries: **%pip install langgraph openai ffmpeg-python requests python-dotenv**

### Step 3: Run the Jupyter Notebook

To execute the notebook, select each cell and press ```Shift + Enter```.
