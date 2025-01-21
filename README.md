# E-Panchayat

E-Panchayat is a web application designed to facilitate the management of complaints and user interactions within a panchayat. The application allows users to register, log complaints, and track their status. It also provides administrative functionalities for managing users and complaints.

## Features

- User registration and login
- Complaint submission and tracking
- Administrative dashboard for managing users and complaints
- PDO dashboard for managing complaints within a specific address
- Feedback submission for resolved complaints

## Technologies Used

- Flask (Python web framework)
- MySQL (Database)
- HTML/CSS (Frontend)

## Setup Instructions

1. **Clone the repository:**
    ```sh
    git clone <repository-url>
    cd Epanchayat
    ```

2. **Install dependencies:**
    Ensure you have Python and pip installed. Then, install the required Python packages:
    ```sh
    pip install flask mysql-connector-python
    ```

3. **Database Setup:**
    - Create a MySQL database named `epanchayat`.
    - Create the necessary tables (`Users`, `Complaints`) as per the application's requirements.

4. **Run the application:**
    ```sh
    python app.py
    ```

5. **Access the application:**
    Open your web browser and navigate to `http://0.0.0.0:5000`.

## Application Routes

- `/` : Login page
- `/signup` : User registration page
- `/home` : User home page for tracking complaints
- `/PDO` : PDO dashboard for managing complaints
- `/complaint` : Page for submitting new complaints
- `/complaintStatus/<Complaintid>` : Page for viewing and updating complaint status
- `/admin` : Admin dashboard for managing users
- `/details` : Page for adding new PDO users
- `/delete/<InetID>` : Route for deleting users
- `/feedback` : Route for submitting feedback on resolved complaints

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License.
