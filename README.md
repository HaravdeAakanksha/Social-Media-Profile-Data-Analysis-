# Social Media Profile Data Analysis | Python

A Python-based data analysis project that extracts and organizes social media profile information from raw text files. The project converts unstructured profile data into structured JSON format and identifies profiles with the highest number of posts, followers, and following, along with the total number of profile categories.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Project Objectives](#project-objectives)
3. [Tools and Technologies](#tools-and-technologies)
4. [Key Features](#key-features)
5. [Data Processing](#data-processing)
6. [Key Findings](#key-findings)
7. [Business Insights](#business-insights)
8. [Project Structure](#project-structure)
9. [How to Run the Project](#how-to-run-the-project)
10. [Conclusion](#conclusion)

## Project Overview

This project uses Python to process social media profile data stored in a text file. It extracts information such as usernames, names, post counts, follower counts, following counts, profile categories, and bios.

The extracted information is organized into structured records and exported to a JSON file. The project also identifies profiles with the highest activity and audience numbers, providing a basic understanding of social media profile analysis.

## Project Objectives

- Extract useful information from unstructured social media profile data.
- Convert text-based profile information into structured data.
- Handle follower and following counts expressed in K and M formats.
- Export processed data into JSON format for further analysis.
- Identify profiles with the highest number of posts, followers, and following.
- Count the different categories represented in the dataset.

## Tools and Technologies

- **Programming Language:** Python
- **Data Format:** TXT and JSON
- **Libraries and Modules:** Python's built-in `json` module
- **Core Concepts:** File Handling, String Manipulation, Functions, Lists, Loops, Dictionaries, Sets, and Data Parsing

## Key Features

### 1. Data Extraction

- Reads social media profile information from a text file.
- Separates individual profiles using line breaks.
- Extracts usernames, names, posts, followers, following, categories, and bios.

### 2. Data Transformation

- Converts post counts into integers.
- Converts follower and following counts into numerical values.
- Handles abbreviated counts such as K (thousands) and M (millions).
- Organizes extracted information into Python dictionaries.

### 3. JSON Export

- Converts structured profile data into JSON format.
- Saves the processed records to a JSON file.
- Makes the data easier to store, reuse, and analyze.

### 4. Profile Analysis

- Identifies the profile with the highest number of posts.
- Identifies the profile with the highest number of followers.
- Identifies the profile following the most accounts.
- Counts the unique profile categories in the dataset.

## Data Processing

The project follows a simple data processing workflow:

1. **Read Data:** Load the raw profile information from a text file.
2. **Split Records:** Separate the text into individual profile sections.
3. **Extract Fields:** Parse the profile details using string operations.
4. **Convert Values:** Transform post, follower, and following counts into numerical values.
5. **Structure Data:** Store the extracted information in dictionaries.
6. **Export Data:** Save the structured records in JSON format.
7. **Analyze Profiles:** Compare profile metrics and identify the highest values.

## Key Findings

The project identifies the following information from the dataset:

- The profile with the highest number of posts.
- The profile with the highest number of followers.
- The profile with the highest number of following.
- The total number of unique profile categories.

*Note: The actual usernames, counts, and category totals depend on the input dataset and can be added after running the code.*

## Business Insights

- **Influencer Identification:** Profiles with high follower counts may be potential candidates for influencer marketing campaigns.
- **Content Activity:** Post counts help compare how actively different profiles publish content.
- **Audience Analysis:** Follower and following counts provide a basic view of profile audience size and networking activity.
- **Category-Based Marketing:** Profile categories can help businesses identify creators relevant to particular products or audiences.
- **Data Organization:** Converting raw text into structured JSON makes profile information easier to reuse in future analytics projects.

These are potential applications of the extracted data, not proof of actual marketing performance.

## Project Structure

```text
Social-Media-Profile-Analysis/
│
├── Data/
│   ├── finaldata.txt
│   └── data.json
│
├── main.py
└── README.md
```

*Note: Update the filenames and structure to match your actual GitHub repository.*

## How to Run the Project

### Prerequisites

- Python 3 installed on your system.
- The input file `finaldata.txt` placed inside the `Data` folder.

### Steps

1. Clone or download the repository.
2. Open the project folder in VS Code or another Python editor.
3. Ensure the input text file is available at `Data/finaldata.txt`.
4. Run the Python script:

```bash
python main.py
```

5. Check the generated JSON file and the console output for the profile analysis results.

**Note:** The script must create the profile records in `all_chunks` before exporting them to JSON or running the analysis loops. Use the appropriate filename for your Python script.

## Conclusion

This project demonstrates how Python can transform unstructured text into organized, reusable data. By extracting profile details, converting numerical values, exporting JSON records, and comparing profile metrics, it provides a practical introduction to data parsing and basic social media analytics.

## Author

**Your Name**
