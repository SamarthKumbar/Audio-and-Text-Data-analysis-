
## Project Overview

### Task 1: Semantic Chunking of a YouTube Video

**Objective:** Extract high-quality, meaningful (semantic) segments from a specified YouTube video.

**Workflow:**

1. **Download Video and Extract Audio:**
   - Download the video and separate the audio component

2. **Transcription of Audio:**
   - Utilize an open-source Speech-to-Text model 

3. **Time-Align Transcript with Audio:**
   - Use tools to align the transcript with the audio, ensuring each word in the transcript corresponds accurately to its place in the audio.

4. **Semantic Chunking of Data:**
   - Slice the data into audio-text pairs, ensuring each audio-chunk is less than 15 seconds in length.
   - Employ semantic information from the text and voice activity information from the audio to determine chunk boundaries.
   - Logic used for semantic chunking involves identifying complete sentences or phrases and avoiding mid-sentence breaks.


### Task 2: Exploratory Data Analysis of New Testament Audio and Text

**Objective:** Conduct a comprehensive exploratory data analysis (EDA) on the audio and text data of the 260 chapters of the New Testament in your mother tongue (excluding English).

**Workflow:**

1. **Web Scraping:**
   - Systematically download the audio files and their corresponding textual content for each of the 260 chapters of the New Testament from Faith Comes By Hearing website using web scraping tools like `BeautifulSoup` and `requests`.

2. **Data Preparation:**
   - Organize the data by chapters, ensuring each audio file is matched with its corresponding text.

3. **Exploratory Data Analysis:**
   - Analyze the data to uncover patterns, anomalies, or insights.
   - Evaluate various facets of the data, including audio quality, text clarity, and alignment between text and spoken content.
   - This analysis can benefit applications like Text to Speech (TTS) and Speech to Text (STT) technologies.



