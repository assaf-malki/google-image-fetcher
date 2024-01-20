# Google Image Fetcher

## Introduction
Google Image Fetcher is an efficient library tailored for scraping images from Google, offering a streamlined solution for collecting a diverse set of images swiftly. This tool is essential for users requiring bulk image data, such as developers working on machine learning models, data analysts, or digital content creators.

## Pre-requisites:
Before you begin, ensure you have the following:
1. Google Chrome installed on your system.
2. Python3 along with these packages: Pillow, Selenium, and Requests.
3. Windows OS (The tool is not tested on other operating systems).

## Setup Instructions:

1. **Open Command Prompt**
    - Navigate to your desired directory.

2. **Clone the Repository**
    ```bash
    git clone https://github.com/assaf-malki/google-image-fetcher
    cd google-image-fetcher
    ```

3. **Install Dependencies**
    - Ensure you have the necessary Python3 packages installed.
    ```bash
    pip install -r requirements.txt
    ```

4. **Configure Parameters**
    - Edit `main.py` to set your scraping parameters:
        ```bash
        search_keys         = [Your search keywords]
        number of images    = [Desired number of images]
        headless            = [Chrome GUI behaviour: True for no GUI]
        min_resolution      = [Minimum image resolution]
        max_resolution      = [Maximum image resolution]
        max_missed          = [Max failed attempts before termination]
        number_of_workers   = [Number of concurrent jobs]
        ```

5. **Run the Program**
    - Execute the script via the command line to start scraping images based on your specified parameters.
    ```bash
    python main.py
    ```

## Usage
Google Image Fetcher is crafted to circumvent the recent scraping restrictions imposed by Google on image data retrieval. Customize your search criteria in `main.py` and execute the script via command line to begin scraping.

### Note:
- The program is designed to run in command line environments and not through IDEs like VSCode.
- An updated webdriver is installed automatically by the program, negating the need for manual installations.
