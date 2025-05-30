# Clickstream Data Analysis

This project analyzes clickstream data to understand user behavior patterns, particularly focusing on watch percentages and Continuous-Time Markov Chain (CTMC) analysis.

## Project Structure

- `generate_watch_percentage_files.ipynb`: Notebook for generating watch percentage data files
- `generate_ctmc.ipynb`: Notebook for CTMC analysis and generation
- `visualize_watch_percentage_cdf.ipynb`: Notebook for visualizing watch percentage cumulative distribution functions
- `exclude_outlier_users.ipynb`: Notebook for identifying and excluding outlier users from the analysis
- `requirements.txt`: Project dependencies

## Setup

1. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Unix/macOS
# or
.\venv\Scripts\activate  # On Windows
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Dependencies

- pandas: Data manipulation and analysis
- matplotlib: Data visualization
- seaborn: Statistical data visualization
- numpy: Numerical computing

## Usage

1. Start with `exclude_outlier_users.ipynb` to clean the data
2. Use `generate_watch_percentage_files.ipynb` to process the raw clickstream data
3. Visualize watch percentage using `visualize_watch_percentage_cdf.ipynb`
4. Use `generate_ctmc.ipynb` for CTMC analysis

## Data

The project requires clickstream data to be placed in the `course_data/` directory. Make sure to place your data files in this directory before running any analysis scripts.

