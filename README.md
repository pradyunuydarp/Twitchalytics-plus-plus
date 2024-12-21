#  Twitchalytics++

## Overview
This project aims to analyze and visualize streamer performance data to gain insights into viewership trends, follower growth, and engagement patterns. The analysis focuses on metrics such as watch time, stream time, peak viewers, and more, leveraging various visualization techniques and statistical methods to uncover key findings.

## Features
- **Comprehensive Analysis**: Includes detailed exploration of streamer data metrics such as `Watch time (Minutes)`, `Stream time (minutes)`, `Followers gained`, and more.
- **Interactive Visualizations**: Utilizes tools like Matplotlib and Seaborn for clear and engaging visual representation.
- **Actionable Insights**: Identifies patterns and trends to inform strategic decisions for streamers and content creators.

## Dataset
The dataset includes the following columns:
- `Channel`: Name of the streamer’s channel.
- `Watch time (Minutes)`: Total watch time accumulated by viewers.
- `Stream time (minutes)`: Total time spent streaming.
- `Peak viewers`: Maximum viewers during a single stream.
- `Average viewers`: Average number of viewers per stream.
- `Followers`: Total followers.
- `Followers gained`: Number of new followers gained.
- `Views gained`: Total views accumulated.
- `Partnered`: Whether the streamer is partnered (Boolean).
- `Mature`: Whether the content is marked as mature (Boolean).
- `Language`: The primary language of the channel.

## Key Insights
- **Viewership Trends**: Analyzed peak and average viewers to identify high-performing streamers.
- **Follower Growth**: Explored relationships between stream time and followers gained.
- **Language Patterns**: Examined how language influences viewer engagement.
- **Partnered Channels**: Assessed the impact of being a partnered channel on key metrics.

## Visualizations
Some of the visualizations created include:
1. Scatter plots to analyze relationships between `Watch time` and `Stream time`.
2. Bar charts showing distribution of `Language` among streamers.
3. Heatmaps to understand correlations between different metrics.
4. Histograms to explore distributions of `Followers gained` and `Views gained`.

## Tools and Technologies
- **Python**: Core programming language for data analysis and visualization.
- **Libraries**:
  - `Pandas`: Data manipulation and analysis.
  - `Matplotlib` and `Seaborn`: For creating visualizations.
  - Other libraries: NumPy, Scikit-learn.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/project-name.git
   ```
2. Navigate to the project directory:
   ```bash
   cd project-name
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Load the dataset into the analysis script.
2. Run the script to generate visualizations and insights.
3. Review the output in the designated folder or interactive notebook.

## Future Work
- Incorporate machine learning models to predict key metrics such as viewer count.
- Expand analysis to include sentiment analysis of streamer content.
- Automate the data visualization process for real-time updates.

## Contributors
- Pradyun
- Tahir
- Narayana

## License
This project is licensed under the MIT License. See the LICENSE file for details.

