# ITPM_Assignment_01_IT23375178_WE_4.2

#  Sinhala Transliteration Accuracy Testing

### IT3040 – ITPM | Assignment 1 (Option 1)

##  Overview

This project evaluates the **accuracy of a Sinhala transliteration system** that converts informal **Singlish (chat-style Sinhala written in English letters)** into Sinhala script.

The system under test:
🔗 [https://www.pixelssuite.com/chat-translator](https://www.pixelssuite.com/chat-translator) 

The main focus is identifying **incorrect transliterations** and validating them using **automated testing**.



##  Objective

The objective of this assignment is to:

* Evaluate the correctness of the **chat-style Sinhala transliteration function**
* Identify **real-world failure scenarios**
* Automate testing using **Playwright**
* Analyze weaknesses in the transliteration process


##  Project Scope

This project includes:

* 50 **negative test cases** (incorrect transliterations)
* Coverage of **24 Singlish input types**
* Automated execution using **Playwright (Python)**
* Result documentation in an **Excel file**



##  Technologies Used

* **Python 3.x**
* **Playwright (Python)**
* **Pytest (optional)**
* **Microsoft Excel**


##  Project Structure


 Sinhala-Transliteration-Testing
│
├──  tests/
│   ├── test_cases.py
│   ├── test_config.py
│
├──  test_automation/
│   ├── playwright scripts
│   ├── config files
│
├──  Assignment 1 - Test cases.xlsx
├──  requirements.txt
├──  README.md
└──  run_tests.py


##  Installation Guide
### 1 Clone the Repository

bash
git clone <https://github.com/Imbulgoda/ITPM_Assignment_01_IT23375178_WE_4.2.git>
cd Sinhala-Transliteration-Testing


### 2 Create Virtual Environment (Recommended)

bash
python -m venv venv
venv\Scripts\activate   # Windows

### 3 Install Dependencies

bash
pip install -r requirements.txt


### 4 Install Playwright Browsers
bash
playwright install



##  Running the Tests

bash
python run_tests.py


OR (if using pytest):

bash
pytest



##  Test Case Design

Each test case includes:

* **TC ID** (Neg_XXXX)
* **Input (Singlish)**
* **Expected Output (Correct Sinhala)**
* **Actual Output**
* **Status (Fail/Pass)**
* **Input Type Covered**
* **Evidence / Rationale**

### Input Length Categories:

* **S** → ≤ 30 characters
* **M** → 31–299 characters
* **L** → 300–450 characters 



##  Covered Singlish Input Types

The system is tested against multiple real-world scenarios including:

* Question forms
* Commands
* Greetings
* Requests & responses
* Slang and casual language
* Romanization variations
* English word insertions
* Emojis
* Dates, time, currency
* URLs, emails, usernames

(Full list based on assignment Appendix 1)



##  Output & Results

* Automated test execution results are recorded in:
   **Assignment 1 - Test cases.xlsx**

* Each test highlights:

  * Transliteration errors
  * Pattern weaknesses
  * Common failure cases



##  Key Findings (Example)

* Difficulty handling **mixed English + Sinhala inputs**
* Errors in **slang and informal phrases**
* Inconsistent handling of **spelling variations**
* Issues with **numbers, emojis, and symbols**



##  Important Notes

* All test cases are **original** (no Appendix examples used)
* Repository is **publicly accessible**
* Plagiarism threshold: **< 10% similarity** 



##  Submission Instructions

1. Rename all files using your **registration number**
2. Create a folder with your registration number
3. Include:

   * Playwright project
   * Excel file
   * GitHub link
4. Compress into a `.zip` file
5. Upload before deadline



##  Author

**Name:** [I G I N Imbulgoda]
**IT Number:** [IT23375178]
**Program:** BSc (Hons) in Information Technology
**Module:** IT3040 – ITPM







