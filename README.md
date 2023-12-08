
# Automate Sending Emails Using Python

## Overview

This Python project automates the process of sending reminder emails based on data from a Google Sheets document.

## Prerequisites

- Python 3.x
- `pandas` library (`pip install pandas`)

## Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/automate-sending-emails.git
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Create a Google Sheets document with the required columns: `due_date`, `reminder_date`, `has_paid`, etc.

4. Make the Google Sheets document public, and note the `SHEET_ID` and `SHEET_NAME`.

5. Update the `main.py` file:

    - Set the `SHEET_ID` and `SHEET_NAME` variables with your Google Sheets information.
    - Customize the email content in `send_email.py`.

6. Test the setup:

    ```bash
    python main.py
    ```

## CSV Representation

Here is a representation of the CSV file structure expected by the script:

```csv
invoice_no,name,email,due_date,reminder_date,has_paid,amount
INV-001,John Doe,john@example.com,2023-01-15,2023-01-10,no,100
INV-002,Jane Smith,jane@example.com,2023-02-20,2023-02-15,no,150
# Add more rows as needed
```

---

Feel free to make any additional adjustments based on your project's specifics. If you have any other questions or need further modifications, let me know!
