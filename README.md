# Project Title
File-Parsing-and-Report-Generation

The Log Parser Project is designed to automate the analysis of server logs, focusing on identifying and counting occurrences of error and warning messages. The result is a detailed report in CSV format, providing system administrators and developers with quick insights into server issues.

# Software Versions
Python: 3.x, Libraries: re, csv, collections.Counter
# Setup Instructions
### 1. Clone the repository

   git clone https://github.com/your-username/your-repository.git
  cd your-repository

### 2. Install the required libraries

  pip install -r requirements.txt
   
### 3. Download the dataset

Ensure that the server_logs.txt file is placed in the root directory of the project. This file should contain the server logs for parsing.

# Project Structure

1. Project-1.ipynb: (Optional) A Jupyter Notebook version of the project, demonstrating each step of the parsing and report generation for interactive testing and analysis.
2. log_parser.py: The main Python script that parses the server log, counts error and warning messages, and outputs the results to a CSV file.
3. server_logs.txt: A sample log file that contains server logs, including info, warnings, and errors.
4. error_report.csv: The output file generated by the script, containing the count of each error or warning message.
5. README.md: This file, providing a comprehensive overview and setup instructions.

# Credits
This project was created by Sai Harshitha Mutyala (https://github.com/saiharshitha82) 
