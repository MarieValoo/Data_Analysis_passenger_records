# Analyzing Passenger Records from the Russian Empire, Austria-Hungary, the Netherlands, Scandinavia, and Other European Countries, ca. 1820 - ca. 1912

This Jupyter notebook examines records and its respective metadata within the first 480 passenger records from the National Archives dataset: Records of Passengers from the Russian Empire, Austria-Hungary, the Netherlands, Scandinavia, and Other European Countries, ca. 1820 - ca. 1912 (titled PAS_RUS). The PAS_RS is one of 4 subset databases of the MS Access database donated to the National Archives, with the three other databases covering Italian passenger records (PAS_IT), UK and Irish passenger records (PAS_UK), and German, French, and Switzerland passenger records (PAS_GS). PAS_RS has the smallest amount of passenger records, containing 835,984 records total, while the three other databases contain two million or more.

## Getting Started

Follow these instructions to set up the project on your local machine and run the Jupyter Notebook.

### Prerequisites

You will need **Python 3.x** installed on your computer. If you don't have it, download it from [python.org](https://python.org).

### Installation & Setup

1. **Clone the repository** (or download the ZIP file):
   ```bash
   git clone https://github.com
   cd Marie_Valouiski_Final
   ```

2. **Create a virtual environment** (Recommended to keep your global Python clean):
   * **Mac/Linux:**
     ```bash
     python3 -m venv venv
     source venv/bin/activate
     ```
   * **Windows:**
     ```bash
     python -m venv venv
     venv\Scripts\activate
     ```

3. **Install the required packages:**
   ```bash
   pip install --upgrade pip
   pip install notebook numpy pandas matplotlib seaborn scikit-learn
   ```

### Running the Notebook

Once the installations are complete, launch Jupyter Notebook by running:

```bash
jupyter notebook
```

This will automatically open your web browser. Click on your `.ipynb` file in the dashboard to open, view, and run the code.
