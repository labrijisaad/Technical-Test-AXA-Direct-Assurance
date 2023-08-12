# Data Science Technical Test Solution (AXA Direct Assurance)

⭐ This repo holds my solution for the Data Science Technical Test from AXA Direct Assurance's DATA/AI team.

## Project Structure
The project is structured as follows:

* `data/`: This directory contains the necessary data files for the analysis. (it is excluded from version control using `.gitignore`.)
* `notebooks/`: This directory contains Jupyter notebooks with the code for the data analysis.
* `results/`: This directory contains the output visualizations generated during the analysis.
* `README.md`: This file provides an overview of the project and instructions on how to reproduce the analysis.
* `.gitignore`: This file contains the list of files that are ignored by git.
* `requirements.txt`: This file contains the list of packages that are required to run the analysis.
* `.env`: This file contains the environment variables used in the analysis.

## Getting Started

To get up and running with the project, follow these steps:

1. **Clone the repository**:

    ```shell
    git clone https://github.com/labrijisaad/data-science-technical-test.git
    ```

2. **Navigate to the project directory**:

    ```shell
    cd data-science-technical-test
    ```

3. **Ensure Python 3.9 is installed**. The required packages are listed in the `requirements.txt` file.

4. **Create a virtual environment** (highly recommended to maintain project isolation):

    ```shell
    python3 -m venv venv
    ```

5. **Activate the virtual environment**:

    - macOS/Linux:

    ```shell
    source venv/bin/activate
    ```

    - Windows:

    ```shell
    venv\Scripts\activate
    ```

6. **Install dependencies** listed in `requirements.txt`:

    ```shell
    pip install -r requirements.txt
    ```

7. **Place the dataset files** within the `data/` directory.

8. **Fire up the Jupyter Notebook server**:

    ```shell
    jupyter notebook
    ```

9. **Explore and analyze** by opening the desired notebook from the `notebooks/` directory.
