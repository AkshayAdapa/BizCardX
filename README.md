<p align="center">
  <img src="https://cdn.veryfi.com/wp-content/uploads/business-card-data-extraction.jpg" alt="BizCardX Logo" width="400">
</p>

<h1 align="center">BizCardX: Extracting Business Card Data with OCR</h1>
<h3 align="right">By Akshay Kumar</h3>

## Overview
- BizCardX is an innovative Streamlit application designed to simplify the extraction and management of business card data using Optical Character Recognition (OCR) technology.
- The application empowers users to upload images of business cards, extract crucial information such as name, company, contact details, etc., and conveniently save it along with the corresponding card image.

## Table of Contents

1. [Introduction](#introduction)
2. [Technologies Used](#technologies-used)
3. [Problem Statement](#problem-statement)
4. [Approach](#approach)
5. [Results](#results)

## Introduction
- Traditional methods of manually transcribing information from business cards are often tedious, error-prone, and time-consuming.
- BizCardX addresses this challenge by automating the extraction process, thereby saving users valuable time and effort.

## Technologies Used
- Python: The core programming language used for application development.
- Streamlit: A powerful framework for building interactive web applications with Python.
- easyOCR: A robust OCR engine for extracting text from images.
- MySQL: A popular relational database management system used for storing extracted information.
- Pandas: A versatile data manipulation library used for handling tabular data.

## Problem Statement
- You have been tasked with developing a Streamlit application that allows users to upload an image of a business card and extract relevant information from it using easyOCR.
- The extracted information should include the company name, card holder name, designation, mobile number, email address, website URL, area, city, state, and pin code.
- The extracted information should then be displayed in the application's graphical user interface (GUI).
- In addition, the application should allow users to save the extracted information into a database along with the uploaded business card image.

## Approach
1. ✅ **Install the required packages:** Install Python, Streamlit, easyOCR, and a database management system like SQLite or MySQL.
2. ✏️ **Design the user interface:** Create a simple and intuitive user interface using Streamlit that guides users through the process of uploading the business card image and extracting its information.
3. 🖼️ **Implement the image processing and OCR:** Use easyOCR to extract the relevant information from the uploaded business card image. Employ image processing techniques like resizing, cropping, and thresholding to enhance the image quality before passing it to the OCR engine.
4. 📋 **Display the extracted information:** Once the information has been extracted, display it in a clean and organized manner in the Streamlit GUI. Utilize widgets like tables, text boxes, and labels to present the information.
5. 💾 **Implement database integration:** Use a database management system like SQLite or MySQL to store the extracted information along with the uploaded business card image. Utilize SQL queries to create tables, insert data, and retrieve data from the database. Implement functionalities to update and delete data through the Streamlit UI.
6. 🧪 **Test the application:** Test the application thoroughly to ensure that it works as expected. Run the application on your local machine and verify its behavior.
7. 🛠️ **Improve the application:** Continuously improve the application by adding new features, optimizing the code, and fixing bugs. Consider adding user authentication and authorization to make the application more secure.

## Results
- The result of the project is a Streamlit application that allows users to upload an image of a business card and extract relevant information from it using easyOCR.
- The extracted information includes the company name, card holder name, designation, mobile number, email address, website URL, area, city, state, and pin code.
- The extracted information is displayed in the application's graphical user interface (GUI).
- The application also allows users to save the extracted information into a database along with the uploaded business card image.
- The database can store multiple entries, each with its own business card image and extracted information.
- The final application has a simple and intuitive user interface that guides users through the process of uploading the business card image and extracting its information.
- The extracted information is displayed in a clean and organized manner, and users can easily add it to the database with the click of a button.
