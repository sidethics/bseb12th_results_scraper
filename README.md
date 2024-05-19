# BSEB 12th Results Scraper

This Python script allows you to scrape student details and subject-wise marks from the Bihar School Examination Board (BSEB) website for 12th-grade results.

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


