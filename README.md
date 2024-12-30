
# CS427-SMU: AI Safety Course

## Overview

This repository contains code and exercises for the CS427 AI Safety course at SMU. The exercises are designed to help students explore various aspects of AI safety, including robustness, backdoor detection, fairness, and privacy.

## Prerequisites

Before you begin, ensure you have Python installed on your system in case you need to run the code locally. However, the primary environment for running the exercises is Google Colab.

## Running Exercises in Google Colab

1. Open the Colab notebook for the specific exercise (e.g., `Week1_Colab`).
2. Save a copy of the notebook to your Google Drive.
3. Follow the instructions provided within the notebook to complete the exercise.

### Local Setup (Optional)

If you'd like to set up a local environment, follow the steps below.

### Step 1: Install Python and Virtual Environment

#### For Windows:
1. Install the virtual environment:
   ```bash
   pip install virtualenv
   ```
2. Create a virtual environment:
   ```bash
   python3 -m virtualenv cs427_venv
   ```
3. Activate the virtual environment:
   ```bash
   .\cs427_venv\Scripts\activate
   ```

#### For MacOS/Linux:
1. Install the virtual environment:
   ```bash
   pip install virtualenv
   ```
2. Create a virtual environment:
   ```bash
   virtualenv -p python3 cs427_venv
   ```
3. Activate the virtual environment:
   ```bash
   source cs427_venv/bin/activate
   ```

---

### Step 2: Install Required Libraries
With the virtual environment activated, install the necessary libraries:
```bash
pip install torch torchvision autograd scipy matplotlib
```

---

## Usage

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd CS427-SMU
   ```

2. Follow the instructions provided in each exercise directory or the Colab notebook to complete the tasks.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Contact

For any queries, feel free to contact the course instructor or teaching assistant via the course communication channels.
