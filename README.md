# YouTube Channel Analytics

This project performs data analysis for several YouTube channels using the YouTube Data API v3. The focus is on gathering channel statistics like subscribers, total views, video count, and analyzing video performance metrics such as likes, comments, and publication trends. Visualizations are created using `Seaborn` and `Matplotlib`.

## Table of Contents
- [Project Overview](#project-overview)
- [Setup Instructions](#setup-instructions)
- [Project Features](#project-features)
- [How to Run](#how-to-run)
- [Libraries Used](#libraries-used)
- [Visualizations](#visualizations)
- [Future Improvements](#future-improvements)

## Project Overview

The project analyzes various Argentine news YouTube channels, including:
- A24
- Infobae
- La Nación
- C5N
- Todo Noticias
- El Peluca Milei

It collects statistics and video details from these channels, helping visualize trends in content and audience engagement.

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/YouTube-Channel-Analytics.git
   cd YouTube-Channel-Analytics
   ```

2. **Install required libraries**:
   ```bash
   pip install google-api-python-client pandas seaborn matplotlib
   ```

3. **Set up YouTube API key**:
   - Go to the [Google API Console](https://console.developers.google.com/).
   - Create a project and enable the YouTube Data API v3.
   - Generate an API key and replace the placeholder `api_key = "Your API Key"` in the script with your API key.

## Project Features

### 1. Channel Statistics
The project gathers the following data for each channel:
- Subscriber count
- Total video count
- Total views

### 2. Video Details
The project retrieves data on individual videos, including:
- Video title
- Published date
- Total views, likes, dislikes, and comments

### 3. Data Visualization
The following visualizations are created using `Seaborn` and `Matplotlib`:
- Subscriber count for each channel
- Views of the top 10 most viewed videos
- Monthly trends in video publishing

## How to Run

1. **Open in Google Colab:
- Go to Google Colab.
- Open the notebook file or copy the Python script code into a new Colab notebook.

2. **Modifying Channel IDs** (optional):
   To analyze different channels, modify the `channel_ids` list in the script by adding or removing channel IDs.

3. **Output**:
   The script will output channel statistics and video details as Pandas DataFrames and generate visualizations.

## Libraries Used

- **googleapiclient**: For interacting with the YouTube Data API v3.
- **pandas**: For data manipulation and analysis.
- **seaborn**: For creating static visualizations.
- **matplotlib**: For generating plots.

## Visualizations

### Subscribers by Channel
Shows the total number of subscribers for each analyzed channel.


### Views for Top 10 Videos
Displays the most viewed videos for the selected channels.


### Monthly Video Publishing Trends
Illustrates the number of videos published each month by the analyzed channels.


## Future Improvements
- Perform trend analysis (e.g., year-over-year growth of subscribers and views).
- Expand the analysis to cover more channels or categories.
- Add sentiment analysis for comments on videos.
