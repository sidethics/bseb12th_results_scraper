# BSEB 12th Results Scraper

This Python script allows you to scrape student details and subject-wise marks from the Bihar School Examination Board (BSEB) website for 12th-grade results.

## Purpose

The purpose of this project is to provide a transparent and open-source tool for retrieving and analyzing student data from the BSEB website. With the BSEB 12th Results Scraper, users can easily fetch student details and subject-wise marks for analysis and further processing. This can be useful for educational institutions, researchers, or anyone interested in analyzing academic performance trends.


## Warnings

- **Use Responsibly**: While this script allows for easy retrieval of student data, it should be used responsibly and ethically. Respect the privacy of students and adhere to all relevant laws and regulations.
- **Rate Limiting**: The BSEB website may have rate limiting or other restrictions on data access. Excessive scraping may result in temporary or permanent bans from the website.
- **Data Accuracy**: While efforts are made to ensure the accuracy of the fetched data, there may be inaccuracies or inconsistencies in the results. Users should verify the data independently before making any decisions based on it.

## Features

- **Roll Code and Roll Number Iteration**: The script iterates through a range of roll codes and a list of roll numbers to fetch student details.
- **API Integration**: Utilizes the BSEB API to retrieve student details and subject-wise marks.
- **Data Processing**: Processes the fetched data and saves it to Excel files for further analysis.
- **Customizable**: You can customize the script to specify the initial and final roll codes, as well as the file containing the list of roll numbers.

## Prerequisites

- Python 3.x
- `pandas` library: Install it using `pip install pandas`
- Internet connection to fetch data from the BSEB website

## Usage

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your-username/bseb12th_results_scraper.git
    ```

2. Navigate to the project directory:

    ```bash
    cd bseb12th_results_scraper
    ```

3. Edit the `wordlist.txt` file to include the list of roll numbers you want to fetch data for.

4. Run the Python script:

    ```bash
    python bseb12th.py
    ```

5. Follow the on-screen instructions to input the initial and final roll codes.

6. The script will fetch student details and subject-wise marks and save them to Excel files.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



