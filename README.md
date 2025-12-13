# CAS API Presentation

This repository contains materials and example code for the CAS API presentation.  
No prior experience with Git or the command line is required.

---

## 1. Install Anaconda (Python)

This project uses **Python** and **Jupyter Notebook**, which are easiest to install via **Anaconda**.

1. Go to the Anaconda download page:  
   👉 https://www.anaconda.com/download

2. Download the installer for your operating system (Windows or macOS).

3. Run the installer and **accept all default options**.

4. Once installation is complete, open **Anaconda Navigator**.

---

## 2. Download This Repository (No Git Required)

You do **not** need Git or Git Bash.

1. Click the green **Code** button near the top of this GitHub page.
2. Select **Download ZIP**.
3. Extract (unzip) the downloaded file to a folder on your computer.

---

## 3. Open Jupyter Notebook

1. Open **Anaconda Navigator**.
2. Click **Launch** under **Jupyter Notebook**.
3. A browser window will open showing your file system.
4. Navigate to the folder where you extracted this repository.
5. Open the notebook file (`.ipynb`) provided in this project.

---

## 4. Get a Google Maps API Key

Some parts of this project require a **Google Maps API key**.

### Step 1: Create a Google Cloud Project
1. Go to:  
   👉 https://console.cloud.google.com/
2. Sign in with your Google account.
3. Create a **new project** (or select an existing one).

### Step 2: Enable the Maps API
1. In the Google Cloud Console, go to **APIs & Services → Library**.
2. Search for **Maps JavaScript API** (or other Maps APIs as instructed).
3. Click **Enable**.

### Step 3: Create an API Key
1. Go to **APIs & Services → Credentials**.
2. Click **Create Credentials → API Key**.
3. Copy your API key and keep it private.

> **Important:** Google may require billing information, but the free tier is usually sufficient for this project.

---

## 5. Add Your API Key to the Notebook

When prompted in the notebook:
- Paste your Google Maps API key into the indicated variable, for example:
  ```python
  GOOGLE_MAPS_API_KEY = "your_api_key_here"
