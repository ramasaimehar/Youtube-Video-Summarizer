# Youtube-Video-Summarizer
This Streamlit app summarizes YouTube videos by downloading audio, transcribing it with AssemblyAI, and generating a summary. Users input a YouTube URL, the app processes the audio, displays the transcription and summary, and provides a downloadable ZIP file with the results.

To use this project:

1. Clone the repository.
2. Open a terminal in the working directory.
3. Run the following command to install the required dependencies:
    ```
    pip install -r requirements.txt
    ```
4. Set the `api_key` (replace `-------YOUR API KEY--------` with your actual API key) in secrets.toml in folder .streamlit file:
    ```
   api_key = '----YOUR API KEY-----'
    ```
5. The `app.py` file contains the Streamlit application.
6. Run the script with the following command:
    ```
    python3 streamlit run app.py
    ```
