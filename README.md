# Enhanced Interactive Learning Assistant

## Description
The **Enhanced Interactive Learning Assistant** is an AI-powered system designed to personalize the learning experience. It takes user inputs like learning topics and objectives, gathers information from various sources (web content, video transcripts, academic papers), and generates a well-structured educational report. The system clarifies user interests, assesses prior knowledge, and presents content in the preferred learning format.

---

## Features
- Accepts user learning topics and objectives.
- Gathers information from multiple research sources:
  - Web content (simulated or API-based).
  - Video transcripts (simulated or API-based).
  - Academic papers (simulated or API-based).
- Interactive questioning system to tailor content to the user:
  - Clarifies user interests and learning goals.
  - Assesses prior knowledge and learning preferences.
- Generates educational reports with:
  - Clear organization and learning progression.
  - Visual aids and diagrams.
  - Citations and references.
  - Suggested resources for further learning.
- Supports follow-up questions to modify and refine the report.

---

## Installation Instructions

### Prerequisites
1. Python 3.x
2. Required Python packages

### Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Enhanced-Interactive-Learning-Assistant.git
    cd Enhanced-Interactive-Learning-Assistant
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # For Linux/MacOS
    venv\Scripts\activate     # For Windows
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the application:
    ```bash
    streamlit run learning_assistant_app.py
    ```

---

## System Architecture
The system is built using the following components:
- **Streamlit**: For the interactive user interface.
- **Wikipedia API**: For retrieving web content summaries.
- **YouTube API (simulated)**: For fetching video transcripts (simulated in the code).
- **Google Scholar API (simulated)**: For retrieving academic research summaries (simulated in the code).

The application allows users to input topics and learning goals, fetches relevant content from simulated sources, and generates a personalized learning report.

---

## Research Methodology
The system collects data from various sources:
1. **Web Content**: Fetched using Wikipedia API.
2. **Video Transcripts**: Simulated in this version (could be implemented with a YouTube API for real transcripts).
3. **Academic Papers**: Simulated in this version (could be implemented with Google Scholar API).

This content is then used to build a comprehensive learning report that is tailored based on the user's profile and preferences.

---

## Personalization Approach
The user’s learning profile is captured using the following:
- **Learning Goal**: What the user wants to achieve.
- **Interest Focus**: Specific areas within the topic the user wants to focus on.
- **Knowledge Level**: The user's current knowledge of the topic (beginner, intermediate, advanced).
- **Preferred Format**: Preferred learning format (text, video, hands-on examples).

This data is used to customize the report and ensure the learning experience is personalized.

---

## Report Generation & Modification Implementation
Once the user has provided their learning objectives, the system fetches relevant data and creates a structured report. The report includes:
- Web content summary with citations.
- Video transcript (simulated).
- Academic paper summary (simulated).
- Visual aids and diagrams (future feature).
- Suggested resources for further reading and learning.

Follow-up questions allow users to refine and modify the content based on their needs.

---

## Limitations & Future Improvements
- **Web Content**: Currently relies on the Wikipedia API, but can be extended to other sources like blogs, articles, etc.
- **Video Transcripts**: Currently simulated, but real transcripts can be fetched from platforms like YouTube or Vimeo.
- **Academic Research**: Currently simulated, but integration with real academic databases (e.g., Google Scholar) can be added.
- **Visual Aids**: Diagrams and charts are placeholders; real visual aids could be generated using tools like Matplotlib or Plotly.
- **Real-time Modifications**: Future versions can support real-time content modification based on follow-up questions.

---

## Sample Input & Output

### Sample Input:
- Topic: **Machine Learning**
- Learning Goal: **Understand the basic concepts of Machine Learning**
- Interest Focus: **Supervised vs Unsupervised learning**
- Knowledge Level: **Beginner**
- Preferred Format: **Text**

### Sample Output:
A generated report that includes:
- A summary of the topic.
- A video transcript introducing the concepts.
- An academic summary explaining the underlying theories.
- Suggested additional resources like books, courses, and articles.

---

## Demo

You can try the application yourself by running it locally as described in the installation instructions. You can see the sample_input.txt file and screenshorts file to understand more.

---

## Technology Stack
- **Frontend**: Streamlit
- **APIs**: Wikipedia API, simulated YouTube and Google Scholar APIs
- **Programming Language**: Python 3.x

---


