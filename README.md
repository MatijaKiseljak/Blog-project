# Blog in DRF (Django REST Framework)

This project is a backend application for a blog platform implemented using Django REST Framework (DRF). It allows users to register, log in, edit profiles, and offers various functionalities for interacting with posts and users.

## Features

- **User Registration:** Users can register to access all the functionalities of the blog platform.

- **Login:** After registration, users can log in to the system to access their user account.

- **Profile Editing:** Registered users have the ability to customize and edit their profiles.

- **Content Filtering:** The platform allows users to filter content based on different categories.

- **Search:** The system provides the ability to quickly and effectively find desired posts or users.

- **Publishing/Deleting/Editing:** All registered users can easily publish, delete, and edit their posts.

- **Comments:** Users can comment on posts to exchange ideas and reactions.

- **Search User Accounts:** Users can search profiles of all registered users to easily discover their content.

- **"Like" Feature:** Users can express their appreciation for posts by clicking the Like button.

## Installation

1. Clone this repository to your machine.

git clone <repo_url>


2. Create a virtual environment (optional but recommended).

python -m venv myenv


3. Activate the virtual environment.

- Windows:

  ```
  myenv\Scripts\activate
  ```

- Linux/Mac:

  ```
  source myenv/bin/activate
  ```

4. Install required packages from `requirements.txt`.

   pip install -r requirements.txt


5. Run the Django server.

   python manage.py runserver


## API Endpoints

- `/api/register/` - User registration
- `/api/login/` - User login
- `/api/users/` - View all user profiles
- `/api/profile/` - View user profile
- `/api/blog/` - View all blogs
- `/api/blog/<id>/` - View individual blog
- `/api/comments/<id>/` - View all comments for a specific blog
- `/api/blog/<id>/like/` - Add a "Like" or "Dislike" for a specific post
