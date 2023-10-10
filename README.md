# ChatSense: WhatsApp Chat Analyzer

ChatSense is a web-based tool built using Streamlit that allows you to analyze and gain insights from your WhatsApp chat data. With ChatSense, you can upload a WhatsApp chat file, visualize chat statistics, and explore chat behavior. Whether you're interested in individual or group chat analysis, ChatSense provides a user-friendly interface for your needs.

## Demo:

You can view a live demo of the ChatSense is [here](https://chatsense.onrender.com/).

## Features

- **Upload WhatsApp Chat**: Easily upload your WhatsApp chat export file in text format (e.g., .txt or .csv).

- **User-Specific Analysis**: Choose a specific user to analyze their chat behavior, or analyze the entire group chat ("Overall").

- **Statistics and Insights**: Get key statistics and insights, including total messages, total words, media messages, and URLs shared by the selected user.

- **Timeline Visualizations**: Explore monthly and daily timelines of messages to see chat activity trends over time.

- **Activity Maps**: Discover the busiest day and month for the selected user with activity maps.

- **Word Clouds**: Visualize word clouds to identify frequently used words by the selected user.

- **Common Words**: See a list of the most common words used by the selected user.

- **Emoji Analysis**: Analyze emoji usage and distribution with pie charts.

## Getting Started

1. Clone this repository:

   ```shell
   git clone <repository-url>

2. Install the required Python packages:
   ```shell
   pip install streamlit matplotlib seaborn
   
3. Run the Streamlit app:
   ```shell
   streamlit run app.py
   
4. Open a web browser and navigate to the provided URL to access the ChatSense app.
   
## Usage

1. Upload your WhatsApp chat export file.

2. Select a user from the dropdown menu or choose "Overall" for group-level analysis.

3. Click the "Show Analysis" button to generate visualizations and insights.

4. Explore the various sections and graphs to gain insights into your WhatsApp chat data.
   
## Customization

You can further customize and extend the functionality of ChatSense by modifying the Python code in the app.py file and adding your own analysis functions to the helper.py module.

## Requirements

1) Python 3.x
2) Streamlit
3) Matplotlib
4) Seaborn
   
