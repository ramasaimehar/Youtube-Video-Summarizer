
# 🎥 YouTube Video Summarizer

**YouTube Video Summarizer** is a Streamlit app that simplifies the process of summarizing YouTube videos. It extracts audio, transcribes it using AssemblyAI, and provides a concise summary of the video's content. Perfect for quick insights into lengthy videos!

---

## 🚀 Features  
- 🎵 Extracts audio from YouTube videos.  
- ✍️ Transcribes audio with **AssemblyAI**.  
- 📄 Summarizes the transcription for quick reading.  
- 📦 Offers a downloadable ZIP file with transcription and summary.  

---

## 🛠️ How to Use  

1. **Clone the repository**:  
    ```bash
    git clone https://github.com/ramasaimehar/Youtube-Video-Summarizer.git
    cd Youtube-Video-Summarizer
    ```

2. **Install dependencies**:  
    ```bash
    pip install -r requirements.txt
    ```

3. **Set up your AssemblyAI API key**:  
   - Visit [AssemblyAI Signup Page](https://www.assemblyai.com/dashboard/signup) and create a free account.  
   - After logging in, navigate to the **API Keys** section of your dashboard.  
   - Copy your API key and create a `.streamlit/secrets.toml` file in the project directory.  
   - Add the following line to the file:  
     ```plaintext
     api_key = "YOUR_API_KEY_HERE"
     ```

4. **Run the app**:  
    ```bash
    streamlit run app.py
    ```

---

## 📋 Project Workflow  
1. Input a YouTube video URL.  
2. The app retrieves the audio and uploads it to AssemblyAI.  
3. AssemblyAI transcribes and summarizes the video content.  
4. View the transcription and summary directly in the app.  
5. Download the results as a ZIP file.  

---

## 🖼️ App Interface  

The app features a simple, user-friendly interface with: 

![image](https://github.com/user-attachments/assets/e629bb4e-4221-4cad-9a21-37f43c49b8cd)

- A **URL input field** in the sidebar.

![image](https://github.com/user-attachments/assets/7aad9cdc-854c-4729-8490-eac81246c347)

- Progress bar for process tracking.

![image](https://github.com/user-attachments/assets/f076032f-21e8-41a5-a7b3-d148d95637f3)

- Output sections for transcription and summary.
  
**Transcribed Text :**

![image](https://github.com/user-attachments/assets/50eca8df-738b-4346-bfaa-93351f642f96)

**Summarized Text :**

![image](https://github.com/user-attachments/assets/7185e6fd-74fd-464c-954b-a71585d5ce72)

---

## 🛠️ Technologies Used  
- **Python**  
- **Streamlit**  
- **pytube** for audio extraction.  
- **AssemblyAI** for transcription and summarization.  

