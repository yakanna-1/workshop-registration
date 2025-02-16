# Online Workshop Registration System

## Introduction
The **Online Workshop Registration System** is a web-based application designed to streamline the process of creating, managing, and registering for workshops. It allows organizers to create workshops and participants to register conveniently through an intuitive user interface.

## Features
- **User-friendly Interface**: Simple and interactive design.
- **Workshop Creation**: Organizers can create and manage workshops.
- **Workshop Registration**: Users can browse available workshops and register online.
- **Dynamic Web Pages**: Uses HTML, CSS, and Flask for frontend and backend integration.
- **Database Integration** (if applicable): Can store and manage registration details.

## Technologies Used
- **Backend**: Python (Flask)
- **Frontend**: HTML, CSS
- **Static Files**: CSS for styling

## File Structure
```
Online Workshop Registration System/
│── app.py                    # Main backend application (Flask)
│── static/
│   └── css/
│       └── style.css         # CSS for frontend styling
│── templates/
│   ├── index.html            # Homepage
│   ├── create_workshop.html  # Workshop creation page
│   ├── register_workshop.html # Workshop registration page
│── Screen Recording.mp4      # Demonstration video
```

## Installation & Setup
1. **Clone the Repository**
   ```sh
   git clone <repository_link>
   cd Online-Workshop-Registration-System
   ```
2. **Install Dependencies**
   ```sh
   pip install flask
   ```
3. **Run the Application**
   ```sh
   python app.py
   ```
4. **Access the System**
   Open a web browser and go to `http://127.0.0.1:5000`

## Usage
- **Organizers**: Can log in and create new workshops.
- **Participants**: Can view available workshops and register.

## Future Enhancements
- Add a database (e.g., SQLite, MySQL) to store registrations.
- Implement authentication for workshop organizers.
- Improve UI with more CSS and JavaScript features.

## License
This project is open-source and free to use under the MIT License.

