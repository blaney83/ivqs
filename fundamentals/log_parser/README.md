# Challenge: Log Parser

# Objective:
Write a Python script that parses a log file and extracts certain information based on specific criteria. The script should demonstrate proficiency in file operations, data parsing, and utilizing Python's built-in capabilities.

# Requirements:

## Log File Format:

The log file will be a plain text file.
Each line in the log file represents a log entry.
Each log entry consists of a timestamp, a log level (INFO, WARNING, ERROR), and a message. Example:
```
2024-02-08 09:15:32, INFO, User logged in successfully.
2024-02-08 09:17:43, WARNING, Disk usage exceeds 85%.
2024-02-08 09:18:21, ERROR, Database connection failed.
```
## Script Functionality:

Read a log file provided as a command-line argument.
Extract and print all ERROR log entries.
Count the number of WARNING messages and display the count.
Identify any log entries that do not follow the prescribed format and print an alert for each such entry.

# Considerations:

- Handle file reading errors gracefully.
- Ensure the script is efficient in handling large files.
- Write clean, readable, and well-commented code.
- *Bonus*: Include unit tests for your script.

# Evaluation Criteria:

*File Handling*: Ability to work with file operations (open, read, etc.).
*Data Parsing*: Proficiency in parsing and processing text data.
*Error Handling*: How well the script handles unexpected situations, like file not found or bad log entry format.
*Code Quality*: Readability, structure, and adherence to Pythonic principles.
*Efficiency*: How well the script performs, especially with large log files.
*Testing*: (Bonus) Quality and coverage of unit tests.