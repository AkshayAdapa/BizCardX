# BizCardX
BizCardX: Extracting Business Card Data with OCR

Table of Contents:

1.Introduction

2.Technologies Used

3.Problem Statement

4.Approach

      1.Installation

      2.User Interface Design

      3.OCR Implementation

      4.Data Display

      5.Database Integration

      6.Testing

      7.Improvement

5.Results

6.Dataset

Introduction:

BizCardX is an innovative Streamlit application designed to simplify the extraction and management of business card data using Optical Character Recognition (OCR) technology. The application empowers users to upload images of business cards, extract crucial information such as name, company, contact details, etc., and conveniently save it along with the corresponding card image.

Technologies Used:
BizCardX harnesses a variety of cutting-edge technologies to deliver a seamless and efficient user experience:

  Python: The core programming language used for application development.
  Streamlit: A powerful framework for building interactive web applications with Python.
  easyOCR: A robust OCR engine for extracting text from images.
  MySQL: A popular relational database management system used for storing extracted information.
  Pandas: A versatile data manipulation library used for handling tabular data.
  
Problem Statement:

Traditional methods of manually transcribing information from business cards are often tedious, error-prone, and time-consuming. BizCardX addresses this challenge by automating the extraction process, thereby saving users valuable time and effort.

Approach:

Installation:

To install BizCardX, users simply need to follow the instructions provided in the README file. The installation process is straightforward and well-documented.

User Interface Design:

The user interface of BizCardX is thoughtfully designed using Streamlit, ensuring a seamless and intuitive experience for users. Various widgets such as file uploaders, buttons, and text boxes are utilized to enhance interactivity.

OCR Implementation:

BizCardX leverages the capabilities of easyOCR to accurately extract text from uploaded business card images. Image processing techniques such as resizing, cropping, and thresholding are employed to enhance the quality of input images before passing them to the OCR engine.

Data Display:

Extracted information is presented in a structured and organized manner within the Streamlit GUI. Widgets such as tables, text boxes, and labels are used to display the information clearly and comprehensively.

Database Integration:

BizCardX seamlessly integrates with MySQL to store the extracted information along with the corresponding card images. SQL queries are utilized to create tables, insert data, and retrieve information from the database.

Testing:

Rigorous testing is conducted to ensure the functionality and reliability of BizCardX under various scenarios. Both unit tests and integration tests are performed to validate the application's behavior.

Improvement:

Continuous improvement efforts are made to enhance the application based on user feedback and emerging requirements. New features are added, existing code is optimized, and bugs are addressed in each iteration.

Results

The culmination of our efforts is a robust and user-friendly application that streamlines the process of extracting and managing business card information. With BizCardX, users can easily upload images, extract data, view it in the application interface, and save it to a database with minimal hassle.

Dataset

BizCardX does not rely on a specific dataset, as it operates on user-uploaded images of business cards. This flexible approach allows users to extract information from a wide range of business card designs and formats, making the application highly versatile and adaptable.
