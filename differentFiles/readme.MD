## Project Title: Data Extraction from PDF Files to Excel

### Introduction:
This project was undertaken as part of a school assignment to extract data from PDF files and organize it into an Excel spreadsheet. The goal was to develop a Python script that automates the process of reading PDF files, extracting specific information, and then saving it into an Excel file.

### Objective:
The main objective of this project was to demonstrate the ability to extract structured data from unstructured PDF documents using Python programming language. By automating the process, it aimed to improve efficiency and accuracy in handling large volumes of data.

### Methodology:
1. **Reading PDF Files:** The PyPDF2 library was used to read the content of PDF files.
2. **Data Extraction:** Specific information such as contract number, organization type, organization ministry, buyer name, and buyer address was extracted from each PDF file.
3. **Processing Data:** Extracted data was processed and organized into lists.
4. **Creating Excel File:** Pandas library was utilized to create a DataFrame from the extracted data, which was then exported to an Excel file.

### Instructions for Use:
1. Ensure Python is installed on your system along with the required libraries: PyPDF2 and Pandas.
2. Place the PDF files containing the data to be extracted in the same directory as the Python script.
3. Run the Python script, which will read the PDF files, extract the required information, and generate an Excel file named "data.xlsx" in the same directory.

### Limitations:
- The script assumes a specific format and structure of the PDF files. Any deviation from this format may result in errors or incorrect data extraction.
- It may not handle complex PDF layouts or variations in text formatting effectively.

### Future Enhancements:
- Implement error handling to deal with unexpected situations during PDF parsing.
- Enhance the script to handle a wider range of PDF file formats and layouts.
- Add support for additional data extraction fields based on user requirements.

### Conclusion:
This project provided valuable hands-on experience in data extraction and automation using Python. While initially developed as a school project, it serves as a foundation for further exploration and development of more sophisticated data processing and analysis tools.
