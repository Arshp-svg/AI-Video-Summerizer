# AI Video Summarizer Agent

Welcome to the **AI Video Summarizer Agent** project! This tool leverages the power of Google Gemini 2.0 Flash Exp and DuckDuckGo to provide advanced video analysis, summarization, and contextual insights. The project allows users to upload video files (MP4, MOV, AVI) and interact with the AI by asking specific questions about the content. The AI not only analyzes the video but also enriches the response using real-time web data gathered via DuckDuckGo for an enhanced understanding of the video context.

## Key Features

- **Video Upload & Playback:** Users can upload video files and play them directly within the app.
- **AI-Powered Video Analysis:** The AI analyzes the video and provides a summary, key insights, and answers to user queries.
- **Real-Time Web Research:** Integrated with DuckDuckGo, the AI performs supplementary web searches to gather additional context, enrich the video analysis, and answer questions based on the latest information.
- **User Interaction:** Users can ask specific questions about the video content and receive detailed, actionable responses based on both the video and external web data.

## How It Works

1. **Upload a Video:** Users upload a video file (MP4, MOV, or AVI) that they want to analyze.
2. **View the Video:** The uploaded video is displayed for playback.
3. **Ask Questions:** Users can enter specific questions or requests regarding the video content. For example, "What are the key moments in this video?" or "Can you explain the concept discussed in the video?"
4. **AI Processing:** The AI, powered by Google Gemini 2.0 Flash Exp, analyzes the video content and prepares a response.
5. **Web Search with DuckDuckGo:** If additional context or information is needed, the AI uses DuckDuckGo to search the web for real-time data, ensuring that the response is up-to-date and enriched with relevant information.
6. **Actionable Insights:** The AI delivers a detailed, user-friendly response, providing insights from both the video and web resources.

## Tech Stack

- **Python:** The backend is built using Python, making it easy to integrate various AI tools and services.
- **Streamlit:** For building an interactive and user-friendly web interface.
- **Google Gemini 2.0 Flash Exp:** A powerful AI model used for video content analysis and summarization.
- **DuckDuckGo:** Integrated as a search tool for real-time web data to enrich the AI’s analysis.
- **dotenv:** For managing sensitive information like API keys securely.
- **Tempfile:** Used to manage temporary video file uploads.

## Setup Instructions

To run this project locally, follow these steps:

### 1. Clone the repository:

```bash
git clone https://github.com/Arshp-svg/AI-Video-Summerizer.git
cd AI-Video-Summerizer 
```

### 2. Install dependencies:
```bash
pip install -r requirements.txt

```

### 3. Setup your Google API Key:
-Create a .env file in the project root directory.
-Add your Google API Key in the .env file:
```bash
GOOGLE_API_KEY=your_google_api_key_here
```

### 4. Run the app:
```bash
streamlit run app.py

```
