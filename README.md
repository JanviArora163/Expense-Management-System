# Expense Management System

Welcome to the Expense Management System – a simple and efficient way to track and manage your expenses. This project is built with a Streamlit frontend for an intuitive user interface and a FastAPI backend for fast and scalable APIs.


## Project Structure

- **frontend/**: Streamlit-based user interface.
- **backend/**: FastAPI backend server logic.
- **tests/**: Unit & integration tests for both frontend and backend.
- **requirements.txt**: All required Python packages.
- **README.md**:  Everything you need to know is right here.


## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/expense-management-system.git
   cd expense-management-system
   ```
1. **Install dependencies:**:   
   ```commandline
    pip install -r requirements.txt
   ```
1. **Run the FastAPI server:**:   
   ```commandline
    uvicorn server.server:app --reload
   ```
1. **Run the Streamlit app:**:   
   ```commandline
    streamlit run frontend/app.py

   ```
