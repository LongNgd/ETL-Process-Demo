# ETL Process Demo

This repository showcases an **ETL (Extract, Transform, Load)** pipeline implemented in Python. It demonstrates how to extract data from JSON files, transform currency values, and load the results into a CSV file. This is part of a professional ETL workflow designed for learning and showcasing purposes.

---

## Project Structure

- **`ETL_Process_Script.py`**: Python script containing the ETL pipeline.
- **`data/`**: Directory containing input JSON files.
- **`output/`**: Directory for storing the processed CSV files and log files.
- **`README.md`**: This documentation file.

---

## Features

1. **Extract**: Aggregates data from multiple JSON files into a unified dataset.
2. **Transform**: Converts market capitalization values into a new currency and rounds to three decimal places.
3. **Load**: Exports the transformed data to a CSV file.
4. **Logging**: Captures the progress of each ETL phase for debugging and tracking.

---

## Prerequisites

- Python 3.x
- Required Libraries: `pandas`, `glob`, `json`, `datetime`

Install the required libraries using:
```bash
pip install pandas
