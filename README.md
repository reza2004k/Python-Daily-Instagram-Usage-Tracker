# 📈 Python Daily Instagram Usage Tracker

This project is a simple, automated tool written in **Python** to help users track and monitor their daily engagement with the Instagram platform. The goal is to provide raw data for self-assessment of social media habits by logging information daily into a structured **Excel file**.

## ✨ Features

* **Daily Logging:** Designed to be run once a day to record the usage status for that specific date.
* **Excel Persistence:** Automatically saves all historical usage data (Date, Status, Duration, etc.) into a single Excel spreadsheet (e.g., `usage_log.xlsx`).
* **Simple Interface:** Uses a command-line interface (CLI) to quickly prompt the user for the day's usage status.
* **Habit Monitoring:** Creates a reliable dataset that can be used later for plotting or data analysis (e.g., "On which days did I use Instagram?").

## 🛠️ Technologies Used

* **Language:** Python 3
* **Libraries:**
    * `pandas` (for creating and manipulating DataFrames to handle Excel data)
    * `openpyxl` (pandas dependency for Excel file management)
    * `datetime` (for timestamping the daily log entry)
* **Data Storage:** Microsoft Excel (`.xlsx` file)

## 🚀 Getting Started

To run and use this daily logging script, follow the instructions below.

### Prerequisites

* Python 3 installed on your system.
* The required data handling libraries:

    ```bash
    pip install pandas openpyxl
    ```

### Installation and Running

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/Python-Daily-Instagram-Usage-Tracker.git](https://github.com/YOUR_USERNAME/Python-Daily-Instagram-Usage-Tracker.git)
    cd Python-Daily-Instagram-Usage-Tracker
    ```
2.  **Ensure Data File is Ready:**
    The script requires a data file to exist. The first time you run it, it should create an Excel file (e.g., `usage_log.xlsx`) with the necessary headers (Date, Used, Duration).
3.  **Daily Execution:**
    Run the Python script once every day:
    ```bash
    python daily_tracker.py
    ```
    (Note: Assuming your main file is named `daily_tracker.py`.)

### Usage Flow

1.  When executed, the script will prompt you (in the console) with a simple question regarding your Instagram usage for the current date.
2.  Based on your input, it will record the **current date**, the **usage status**, and any other required details (like time spent).
3.  The data will be appended as a new row to the `usage_log.xlsx` file.

---
