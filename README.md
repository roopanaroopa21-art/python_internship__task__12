# API Data Fetch Project (Python)

This project demonstrates how to fetch data from a *public REST API* using Python, process the JSON response, handle errors gracefully, and store the fetched data locally.

It is beginner-friendly and focuses on real-world API interaction using the requests library.

---

## 📌 Features

- Sends HTTP *GET requests* to a public API  
- Checks and handles *API response status codes*
- Parses *JSON data* into Python dictionaries
- Extracts required fields from *nested JSON*
- Handles network and parsing errors gracefully
- Displays *clean, formatted output*
- Stores fetched data in a *local JSON file*

---

## 🛠 Technologies Used

- Python 3
- requests library
- Public API: *Random User API*

---

## 📂 Project Structure
api-data-fetch/ │ ├── api_data_fetch.py     # Main Python script ├── user_data.json        # Output file (generated after execution) └── README.md             # Project documentation
Copy code

---

## 🚀 How to Run the Project

### 1️⃣ Install Python (if not installed)
Download from: https://www.python.org/

---

### 2️⃣ Install Required Library

```bash
pip install requests
3️⃣ Run the Script
Copy code
Bash
python api_data_fetch.py
📤 Sample Output
Copy code

Fetched User Details
------------------------------
Full Name: Mr John Doe
Gender: male
Email: john.doe@example.com
Country: United States
Username: johndoe123
A file named user_data.json will be created with the fetched details.
📁 Output File Example (user_data.json)
Copy code
Json
{
    "full_name": "Mr John Doe",
    "gender": "male",
    "email": "john.doe@example.com",
    "country": "United States",
    "username": "johndoe123"
}
⚠️ Error Handling
The project safely handles:
Network connection errors
API failures
Invalid or missing JSON data
File writing issues
🎯 Learning Outcomes
Understanding REST APIs
Working with JSON in Python
Using requests library
Writing clean, modular Python code
Basic error handling techniques
📌 Future Improvements
Add unit tests
Support multiple APIs (Weather, Quotes)
Add command-line arguments
Implement logging
📜 License
This project is for learning and educational purposes.
🙌 Author
Roopa N A
Learning Python & API integration 🚀
