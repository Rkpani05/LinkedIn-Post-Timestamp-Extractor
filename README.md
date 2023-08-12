# LinkedIn Post Timestamp Extractor

This tool allows users to extract timestamps from LinkedIn posts. It provides two main functionalities:

1. Extracting the timestamp from a single LinkedIn URL.
2. Extracting timestamps from multiple LinkedIn URLs provided in an Excel file.
   
## Table of Contents

* Installation
* Usage
  * Single URL Timestamp Extractor
  * Multiple URLs Timestamp Extractor
* Benefits
* Contact
  
## Installation

1. Clone the repository or download the source code.
2. Navigate to the project directory.
2. Install the required libraries using the requirements.txt file:
   
```pip install -r requirements.txt```

## Usage
### Single URL Timestamp Extractor

1. Launch the application.
2. Click on the "Single Link" button.
3. Enter the LinkedIn URL in the provided field.
4. Choose the desired timezone (UTC or IST) from the dropdown.
5. Click "Submit" to view the post's timestamp.
   
## Multiple URLs Timestamp Extractor

1. Prepare an Excel file with at least two columns:
__ID:__ A unique identifier for each row.
__URL:__ The LinkedIn URL containing the post ID.
2. Launch the application.
3. Click on the "Multiple Links" button.
4. Click on "Import & Process Excel" and select the prepared Excel file.
5. The program will process the file, extract timestamps, and display them in the "Timestamp UTC" and "Timestamp IST" columns. If you add new URLs to the Excel file and process it again, the program will extract timestamps for the new URLs and display them alongside the previously processed ones.

## Benefits

__Efficiency:__ Quickly extract timestamps from multiple LinkedIn posts without manual effort.

__Flexibility:__ Choose between UTC and IST timezones for timestamp extraction.

__Reusability:__ Process the same Excel file multiple times; the program will identify and extract timestamps for new URLs without affecting previously processed ones.

## Contact
For any queries or feedback, please reach out to rk.pani2002@gmail.com
