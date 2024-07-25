# MapValue - Web Scraping Component

This project is designed to scrape house pricing data for Alexandria and save it into a CSV file. The collected data will be used for further analysis and model training to predict house prices.

## Project Structure

- `data/`: Directory to store scraped data.
- `notebooks/`: Jupyter notebooks for web scraping.
- `requirements.txt`: List of dependencies.
- `README.md`: Project description and instructions.
- `.gitignore`: Files and directories to ignore in Git.

## Setup Instructions

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/Ziad-Thabet/web_scraping.git
    ```

2. **Navigate to the Project Directory**:
    ```sh
    cd web_scraping
    ```

3. **Create a Virtual Environment and Activate It**:
    ```sh
    python -m venv venv
    source venv/bin/activate
    ```

4. **Install the Dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

5. **Start Jupyter Notebook**:
    ```sh
    jupyter notebook
    ```

## Using the Web Scraping Notebook

1. **Open the Jupyter Notebook**:
    - In your terminal or command prompt, navigate to the `notebooks/` directory:
      ```sh
      cd notebooks
      ```
    - Start Jupyter Notebook:
      ```sh
      jupyter notebook
      ```
    - Open `web_scraping.ipynb` from the Jupyter Notebook interface.

2. **Run the Cells in the Notebook**:
    - The notebook will fetch house listings from the specified URL.
    - It will extract house size, price, and location.
    - The scraped data will be saved into a CSV file located in the `data/` directory.
    - The first few rows of the scraped data will be displayed.

## Dependencies

The project requires the following Python libraries:
- `requests`
- `beautifulsoup4`
- `pandas`

These are listed in the `requirements.txt` file and can be installed using:
```sh
pip install -r requirements.txt