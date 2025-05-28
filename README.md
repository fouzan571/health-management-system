# health-management-system
A simple console-based Health Management System in Python to log and retrieve food and exercise data for multiple users with timestamps.

# Health Management System 🏥

This is a basic *Health Management System* built with Python. It allows users to *log* and *retrieve* their *food intake* and *exercise routines* with an accurate timestamp using the built-in datetime module.

## 🔧 Features

- Select between multiple users (e.g., Nilesh, Shanu)
- Choose between logging or retrieving data
- Record entries for:
  - Food
  - Exercise
- Automatically adds the date and time of each entry
- Stores data in separate .txt files for each user and activity

## 🧠 How It Works

The program uses a simple command-line interface:

1. *Select user* – Choose between predefined users.
2. *Choose action* – Log new data or retrieve past entries.
3. *Choose category* – Food or Exercise.
4. Based on your input, the data is either:
   - Logged with a timestamp in a text file, or
   - Retrieved and printed from a text file.

## 📁 File Structure

Each action creates or reads from the following files:

## 🛠 Technologies Used

- Python 3
- Built-in datetime module
- File handling with .txt files

## 💡 Future Enhancements

- Add a user registration system
- Use JSON or SQLite for better data management
- Add a GUI using Tkinter or Streamlit

## 📌 Usage

Run the script using:

```bash
python health_management.py
