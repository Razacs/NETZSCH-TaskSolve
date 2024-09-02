**NETZSCH Solution**
--------------------------------------

This repository contains solution Tasks 1) Test Case Development and Documentation 2) Test Automation 3) Error Analysis and Report.

Solution of NETZSCH Tasks.pdf contains all solution details with proper documentation (Specially Task 01 and Task03).

**Task 02: Automation Test Scripts:**

That contains automated test scripts to validate CSV data processing functions using pytest

Tools and Technologies
Language: Python

Framework Approach
The test automation framework follows Pytest to enhance code reusability, maintainability, and readability. It's designed to organize the test scripts effectively.

**Folder Struture & Test Cases:**

data folder contains all CSV test data & tests folder contains python script.

/NETSZCH
    /tests
        /data
            valid_data.csv
            invalid_format.csv
            missing_fields.csv
            duplicate_data.csv
            sql_injection.csv
        test_csv_import.py
    /pytest.ini

**Setup and Execution Steps**

For execution these steps need to follow:

1.	pip install pytest
2.	cd /NETSZCH
3.	Run this command ‘pytest’

**Execution of Result:**


![image](https://github.com/user-attachments/assets/11de3f18-b406-466d-81f0-cd3cbdb21f2d)

![image](https://github.com/user-attachments/assets/53e83bb3-9f53-4e1f-b72e-5b3781ae159e)

Let me know if you need further information from my side.
Thanks!
