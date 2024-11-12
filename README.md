
# ByteConnect

Welcome to the **ByteConnect**! This platform allows developers to create rooms and chat about different topics. It's built using Django and its template engine, providing an interactive environment for developers to collaborate.

## Features

- **Create Rooms**: Developers can create rooms dedicated to specific topics.
- **Join Rooms**: Users can join existing rooms to participate in conversations.
- **Send Messages**: Users can send messages within the rooms.

## Tech Stack

- **Backend**: Django (Python Framework)
- **Frontend**: HTML, CSS, JavaScript (Django Template Engine)
- **Database**: SQLite (or PostgreSQL for production)

## Getting Started

Follow these instructions to set up the platform locally:

### Prerequisites

Make sure you have the following installed:

- Python (version 3.8 or higher)
- Django (version 3.x or higher)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ByteConnect.git
   cd ByteConnect
   ```

2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Apply migrations to set up the database:
   ```bash
   python manage.py migrate
   ```
5. Run the development server:
   ```bash
   python manage.py runserver
   ```

6. Visit the platform on `http://127.0.0.1:8000/` to start using the platform.

## Screenshots

### Dashboard
![Dashboard](https://github.com/user-attachments/assets/ef69337b-6330-411a-9aab-313598c49de8)


### Room Creation
![Screenshot 2024-11-12 162145](https://github.com/user-attachments/assets/d40544f3-a1f8-4d92-91d4-46d3422deb98)

### Chat Interface
![Screenshot 2024-11-12 160909](https://github.com/user-attachments/assets/2cdf22d1-5b86-4602-9fed-f20a0dfe9bf1)

### Profile Page
![Screenshot 2024-11-12 161608](https://github.com/user-attachments/assets/ff2101e5-2353-4482-a96b-9fa396a76988)

### Admin Panel
![Screenshot 2024-11-12 162016](https://github.com/user-attachments/assets/655a0219-e7f9-40de-a229-27b372c15699)


## Future Enhancements

- **Follow Rooms**: Users will be able to follow specific rooms to receive real-time updates when new messages are posted.
- **Email Notifications**: When a user follows a room, they will receive email notifications for new messages.
- **User Authentication**: Implement user sign-up and login functionality to personalize experience and manage followed rooms.
- **File Sharing**: Option to upload files or images in the chat.

## Contributing

We welcome contributions! Please fork the repository, create a new branch, and submit a pull request with your changes. Ensure your code is well-documented and tested.

## License

This project is licensed under the MIT License.
