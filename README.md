# Task Manager

A fully functional task manager application built with **Flask**.  
This project includes user authentication, task management, and a responsive UI.  
I built and configured this as part of my portfolio to demonstrate my backend and frontend development skills.

---

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Demonstration](#demonstration)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Features

- User Authentication: Login/Logout, user-specific tasks
- Task Management: Add, delete, mark complete
- Responsive UI with light/dark theme
- SQLite database for persistent data
- Secure password hashing
---

## Installation

Follow these steps to set up the project locally:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/srujan096/Fask-task-manager.git
    cd task-manager
    ```

2. **Create a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Initialize the database**:
    Ensure the `instance` directory exists and the SQLite database is initialized:
    ```bash
    python app.py
    ```

5. **Run the application**:
    ```bash
    python app.py
    ```

6. **Open your browser and navigate to**:
    ```
    http://127.0.0.1:5001
    ```

---

## Usage

- **Register**:
  - Navigate to `/register` to create a new account.
  - Fill in the username, password, and confirm password fields.
  - Submit the form to register a new user.
- **Login**:
  - Use the credentials created during registration to log in.
  - If you don't have an account, click on the "Register here" link to create one.
- **Home Page**:
  - View and manage your tasks.
- **Add Task**:
  - Use the input field to add a new task.
- **Delete Task**:
  - Click on a task to delete it.
- **Logout**:
  - Use the logout button (👋) in the top-right corner to log out.

---

## Demonstration

### Login Page
![Login Page](https://github.com/user-attachments/assets/2b718a69-ecc3-4728-8eb5-65c01f6d50f9)

### Registration Page
![Registration Page](https://github.com/user-attachments/assets/c644ed71-49d2-40ca-a8c7-c64d15da0848)

### Task Manager
![Task Manager](https://github.com/user-attachments/assets/c640f797-023c-4c35-a79f-e3854c787b52)

---

## Technologies Used

- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite
- **Environment Management**: Virtualenv

---

## Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

Please make sure your code follows the project's coding standards and includes tests if applicable.


---

## Contact
- **Name:** Srujan Surya  
- **Email**: suryasrujan700@gmail.com
- **GitHub**:(https://github.com/srujan096)

---

Happy coding! 😊
