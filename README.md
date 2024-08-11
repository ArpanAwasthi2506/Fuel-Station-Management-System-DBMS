@@ Fuel Station Management System 

@@ FrontEnd

In this project, the frontend is implemented using the popular Python library, Streamlit.

Streamlit is an open-source app framework in Python that enables quick creation of web apps for data science and machine learning. It is compatible with major Python libraries such as scikit-learn, Keras, PyTorch, SymPy (latex), NumPy, pandas, and Matplotlib.

We can perform operations such as Create, Read, Update, and Delete, commonly known as CRUD operations.

Additionally, there is a user-defined function that calculates the total price in the Tanker table. A trigger is also preset in the Employee table, which activates when someone attempts to update the salary field if the salary is less than 300,000. 

@@ Backend

- In Backend creation of table and table population is done in MySQL 
- It also uses libraries such as Pandas, sql connector, Streamlit 
- It is mostly done Using Python Language. 

@@ Project File Structure 

@@ In Projets folder the following files are present 
1-create_database.py: This script is used to create the Petrolpump_Management database.
2-app.py: This is the main file that you need to run after creating the database. It contains the code for the GUI.
3-databases.py: This file contains all the important function calls related to database operations.
4-create.py: This script creates new table rows when you need to add new data.
5-delete.py: This script implements the delete function used for removing specific rows from the table.
6-read.py: This script reads data from the table and sends it to the view function for display.
7-update.py: This script updates the data in the table.

@@ How TO RUN 
- First create databases using Create_database.py
- Install all the librarys
- run app.py file using command: "Python -m streamlit run app.py"
