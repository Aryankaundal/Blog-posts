# Blog Website

A simple and extensible blog website built using Python and Flask. This project lets users read, create, edit, and manage blog posts through a modern web interface.

## Features

- Create, edit, and delete blog posts
- User registration and login functionality
- Responsive design for desktop and mobile devices
- Markdown or rich text support in posts
- Search and filter functionality
- Admin dashboard for managing content

## Tech Stack

| Component           | Stack/Tool            |
|---------------------|-----------------------|
| Backend             | Python, Flask         |
| Database            | SQLite / PostgreSQL   |
| Frontend            | HTML, CSS, Bootstrap  |
| ORM                 | SQLAlchemy            |
| Authentication      | Flask-Login           |

## Getting Started

### Prerequisites

- Python 3.12
- pip (Python package manager)

### Installation

1. **Clone the Repository**
    ```
    git clone https://github.com/yourusername/blog-website.git
    cd blog-website
    ```

2. **Set Up Virtual Environment**
    ```
    python3.12 -m venv .venv
    source .venv/bin/activate    # On Windows: .venv\Scripts\activate
    ```

3. **Install Dependencies**
    ```
    pip install -r requirements.txt
    ```

4. **Database Migration**
    ```
    flask db init
    flask db migrate
    flask db upgrade
    ```

5. **Run the Application**
    ```
    flask run
    ```
    The site will be available at `http://localhost:5000`.

### Deployment

To deploy on platforms like Render, set the `PYTHON_VERSION` to `3.12.0` in the environment variables or add a `.python-version` file:
