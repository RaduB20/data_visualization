# Interactive Visualization: Social Media & News Consumption

This project provides an interactive and insightful data visualization of the [Social Media and News Fact Sheet](https://www.pewresearch.org/journalism/fact-sheet/social-media-and-news-fact-sheet/) published by the Pew Research Center.

The primary goal is to transform static data into dynamic, interactive plots to reveal deeper insights into how people consume news across different social media platforms.

## Key Features & Visualizations

The main notebook (`data_visualization.ipynb`) contains several interactive plots, including:

- **Waffle Charts (PyWaffle)**: Visualizes the percentage of U.S. adults who get news "Often," "Sometimes," "Rarely," or "Never" from social media, showing trends from 2020 to 2025.

- **Interactive Grouped Bar Charts (Plotly)**: Compares the percentage of U.S. adults who regularly get news from specific social media sites (e.g., Facebook, YouTube, TikTok) over time.

- **Candlestick Charts (Plotly)**: Displays the trend (open, high, low, close) of news consumption among users of each platform from 2020 to 2025.

- **Interactive Horizontal Bar Charts (Plotly)**: Provides a demographic breakdown of regular news consumers on each platform by race (White, Black, Hispanic, Asian).

- **Demographic Spider Charts (Plotly)**: A 2x2 grid of interactive radar charts comparing news consumption on each platform by Gender, Age Group, Political Affiliation, and Education.

## Technologies Used

- **Data Analysis & Manipulation**: Pandas

- **Interactive Visualizations**: Plotly

- **Proportional Visualizations**: PyWaffle

- **Environment**: Jupyter Notebook

## Project Structure

- `/data_visualization.ipynb`: **(Main File)** The Jupyter Notebook containing all data loading, processing, and interactive visualization code.

- `/data/`: Folder containing the raw `.csv` data used in the analysis, sourced from the Pew Research Center.

- `*.png`, `*.pdf`: Static images and exports providing a quick, non-interactive overview of the final results.
