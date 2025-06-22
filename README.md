# excel_to_python_data

A Python utility that converts data copied from Excel spreadsheets into a formatted Python list or array. This tool is ideal for quickly transferring numerical data from Excel into Python scripts, streamlining data processing and analysis tasks.

## Features

- **Graphical Interface:** Opens a simple dialog window where you can paste your copied Excel data.
- **Flexible Parsing:** Handles both tab- and newline-separated values, supporting a variety of Excel copy formats.
- **Automatic Type Conversion:** Converts values to `int` or `float` as appropriate, ignoring non-numeric entries.
- **Convenient Output:** Prints the formatted Python array directly to the console.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/martinedb/excel_to_python_data.git
   cd excel_to_python_data
   ```

2. **Install dependencies:**  
   This script uses Python’s built-in `tkinter` library. No additional packages are required for standard Python distributions.

## Usage

1. Run the script:
   ```bash
   python excel_to_python_data_conv.py
   ```

2. When prompted, paste your copied Excel data into the dialog window and press OK.

3. The script will output a Python array in your terminal.

## Other ways to Run the Script

1. Open up a Jupyter Notebook through Google Colab or Anaconda to run the script.

### Example

Suppose you copy the following data from Excel:

```
1.5    2    3.25
4      5    6
```

After pasting and submitting, the script will print:

```python
Converted Array:
[1.5, 2, 3.25, 4, 5, 6]
```

## License

This project is licensed under the terms of the [MIT License](LICENSE).
