
# Tayara Scraping Project

This project is a Python-based web scraper designed to extract product details and associated images from the Tayara website. It uses Selenium to automate the browser interaction for data scraping and downloading images. The code is implemented in Jupyter Notebooks to showcase step-by-step processes for data collection, image handling, and export.

---

## Features

- **Web Scraping**: Automates product detail and image extraction from Tayara using Selenium.
- **Browser Automation**: Uses Selenium WebDriver for dynamic web content scraping.
- **Image Handling**: Downloads product images and organizes them locally.
- **Data Storage**: Exports the scraped data into structured formats like CSV or JSON.
- **Modular Design**: Code is structured for easy customization and adaptation to other websites.

---

## Technologies Used

- **Python**: Core programming language.
- **Jupyter Notebook**: Interactive environment for running Python code.
- **Selenium**: For browser automation and interaction.
- **Pandas**: For data manipulation and export.
- **OS**: For managing local image storage.

---

## Installation and Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/fedei10/tayara.tn_scraping
   cd tayara-scraping
   ```

2. **Install Required Libraries**:
   Run the following command to install the dependencies:
   ```bash
   pip install selenium pandas
   ```

3. **Set Up Selenium WebDriver**:
   - Download the appropriate WebDriver for your browser (e.g., ChromeDriver for Google Chrome).
   - Ensure the WebDriver is in your system's PATH or place it in the project directory.

4. **Usage**:
   Open the provided Jupyter Notebooks (`tayara_scraping.ipynb` and `tayara_ImageDownload.ipynb`) in your preferred environment (e.g., Jupyter Notebook, JupyterLab).

   - **tayara_scraping.ipynb**:
     - Automates the scraping of product details such as titles, prices, and descriptions.
     - Exports the scraped data into structured format (CSV).

   - **tayara_ImageDownload.ipynb**:
     - Automates the downloading of product images and organizes them in a specified local directory.

5. **Run the Notebooks**:
   - Launch Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
   - Open the respective notebooks and execute the cells step by step.

6. **Exported Data**:
   - Scraped data is saved as `tayara_vehicles.csv`.
   - Images are saved in a structured directory format for easy access.
