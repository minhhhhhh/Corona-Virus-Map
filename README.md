# Corona-Virus-Map
# Corona Virus Map

A Python-based data analysis and visualization project that maps COVID-19 statistics, including city-level connections and distances, to assist with geographical and epidemiological insights.

---

## Features

- **Data Visualization:** Generate a visual map of cities and COVID-19 connections using Python libraries.
- **Graph Algorithms:** Implements graph-based analysis using NetworkX.
- **Geographical Insights:** Analyzes data from CSV files and displays connections on a Texas state map.
- **Dynamic Imports:** Utilizes dynamic data import through Google Drive integration.

---

## Installation

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd Corona_Virus_Map
   ```

2. Install required dependencies:
   ```bash
   pip install matplotlib pandas networkx
   ```

3. Ensure you have access to the required data files:
   - `cities.csv`
   - `distance.csv`
   - `texas-map.png`

4. Update the file paths in the script to match your local or Google Drive setup.

---

## Usage

1. Mount your Google Drive to access the dataset:
   ```python
   from google.colab import drive
   drive.mount('/content/gdrive')
   ```

2. Run the notebook to load data, process connections, and visualize the map.

3. Customize parameters like file paths and visualization settings in the notebook cells.

---

## Dependencies

- **Python 3.7+**
- Libraries:
  - `matplotlib`
  - `pandas`
  - `networkx`
  - `heapq`
  - `queue`

---

## Contributing

Contributions are welcome! Please submit a pull request with detailed descriptions of your updates or fixes.

---

