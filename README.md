# BizCardX: Extracting Business Card Data with OCR

# Introduction:
The objective of this project is to develop a Streamlit application that enables users to upload a business card image and extract essential information from it using easyOCR. The extracted information includes the company name, card holder name, designation, mobile number, email address, website URL, area, city, state, and pin code. The extracted details will be displayed in a user-friendly graphical user interface (GUI).

# Tools:

* Python
* Streamlit
* EasyOCR
* MySQL

# Features

==>> Extracts text information from business card images using EasyOCR.
==>> Utilizes OpenCV for image preprocessing, such as resizing, cropping, and enhancing.
==>> Uses regular expressions (RegEx) to parse and extract specific fields like name, designation, company, contact details, etc.
==>> Stores the extracted information in a MySQL database for easy retrieval and analysis.
==>> Provides a user-friendly interface built with Streamlit to upload images, extract information, alter and delete in the database.

# Workflow:

1. Imported the necessary libraries for the project, including pandas, numpy, streamlit, easyocr, PIL, io, cv2, and re.

2. Set up the required configurations and established a connection with the MySQL database.

3. Created a dictionary to store the extracted data, including fields such as card_holder_name,designation,phone,mail,website,area,city,state,pincode,company_name from business_cards

4. Developed the user interface using Streamlit. Created different pages for the application: "HOME", "UPLOAD", "ALTER" and "DELETE".

5. In the "HOME" page, displays a welcome message and provides basic information about the application.

6. In the "UPLOAD" page, user to upload an image of a business card and extract the card details with view option.

7. If "ALTER" is page, the existing information for a specific person from the database is retrieved. The retrieved information is displayed and users were allowed to alter the desired fields.

8. If "DELETE" is page, the existing information for a specific person from the database were retrieved. The retrieved information was displayed and provided a button labeled "DELETE" to remove the record from the database.

>>> With this project workflow, users can effortlessly extract information from business cards, view  modify and delete the extracted data, and store it in a MySQL database for efficient management and future reference. <<<

 
