# README to Setup Jupyter Notebook

## 1. Prerequisites

- Ensure that **Python** is already installed on your PC/Laptop and accessible via command prompt/console terminal.

## 2. Setup Instructions

Follow these steps to set up the Jupyter Notebook:

### a) Create a Virtual Environment

1. Open the **Command Prompt**.
2. Run the following command to create a virtual environment:
    ```bash
    python -m venv ege356assn2
    ```
3. Navigate to the `ege356` folder:
    ```bash
    cd ege356assn2
    ```
4. Activate the virtual environment by running:
    - On Windows:
      ```bash
      scripts\activate
      ```
    - On macOS/Linux:
      ```bash
      source bin/activate
      ```

### b) Clone the GitHub Repository

1. Run the following command to clone the required repository:
    ```bash
    cd ..
    git clone https://github.com/jhchng/pynb_mqtt_assn2.git
    ```
2. Change to the project directory:
    ```bash
    cd pynb_mqtt_assn2
    ```

### c) Install the Required Dependencies

1. Install the required dependencies by running:
    ```bash
    pip install -r requirements.txt
    ```

### d) Launch the Jupyter Notebook

1. Run the following command to launch the notebook:
    ```bash
    jupyter notebook mqttpubsub.ipynb
    ```

Jupyter Notebook should now be up and running and you should be able to access it.


