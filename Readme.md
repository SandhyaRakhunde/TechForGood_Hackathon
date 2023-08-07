# REST API

## Endpoints for Job Postings

### 1. Login/Register Operations

- **POST** `/api/signup`: Create a new user.
- **POST** `/api/login`: Login a prior user.

### 2. Jobs CRUD Operations

- **GET** `/jobs`: Get a list of all job postings.
- **GET** `/jobs/:id`: Get details of a specific job posting.
- **POST** `/jobs`: Create a new job posting.
- **PUT** `/jobs/:id`: Update all fields of a specific job posting.
- **DELETE** `/jobs/:id`: Delete a specific job posting.

### 3. Jobs Search

- **GET** `/jobs/search/categories/:category`: Search all jobs based on category.
- **GET** `/jobs/search/locations/:location`: Search all jobs based on location.
- **GET** `/jobs/search/titles/:title`: Search all jobs based on title.

### 4. Suggest Domestic Jobs

- **GET** `/jobs/suggest/categories`: Get all the suggested category names in which jobs can be found.
- **GET** `/jobs/suggest/categories/:category`: Get all the suggested jobs from the selected category name.

---

## 🚀 Getting Started

To run the Saksham Gram Mahila application on your local machine, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/saksham-gram-mahila.git`
2. Install dependencies: `cd saksham-gram-mahila && npm install`
3. Set up the database: Ensure MongoDB is installed and running. Create a `.env` file and add your database connection string.
4. Start the server: `npm start`
5. Open `http://localhost:5000` in your web browser.

