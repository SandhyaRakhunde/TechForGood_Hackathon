# Saksham Gram Mahila 🏠

*Saksham Gram Mahila* is a web application aimed at empowering women in rural areas by providing them with domestic job opportunities, homemade products or services to sell, and seasonal work options. The platform serves as a bridge between job seekers and employers, enabling women to showcase their talents and find suitable work in their local communities.

- Easy access, posting, and selling home products through the web application.
- Empowering women in rural areas with diverse job opportunities.
- Striving to create a positive impact on women's lives.
- Contributing to the sustainable development of rural areas.

## Features ✨

- :writing_hand: **Post Domestic Jobs:** Employers can post domestic jobs available around them or from anywhere, providing opportunities for women across regions to find work.

- :package: **Post Domestic Service Requirement or Products to Sell:** Users can post requirements for domestic services they need or homemade products they want to sell, promoting entrepreneurship and empowering women.

- :mag_right: **Skill-based Job Matching:** Women can take a skill assessment quiz, and the platform suggests domestic jobs matching their skillset.

- :round_pushpin: **Location-based Job Search:** Users can search for domestic jobs available in their nearest locations, ensuring convenience and accessibility.

- :bookmark_tabs: **Category-based Job Search:** Women can search for domestic jobs based on specific categories, such as services or products to sell, as well as by the required job title.

## Tech Stack 🛠️

- **Frontend:** HTML, CSS, JavaScript, React.js
- **Backend:** Node.js, Express.js, Postman
- **Database:** MongoDB
- **Additional Tools:** Git, GitHub

## Screenshots -

![image](https://github.com/SandhyaRakhunde/TechForGood_Hackathon/assets/84397275/0d80224b-eb01-484b-bbe8-11bf6e7cb020)

![image](https://github.com/SandhyaRakhunde/TechForGood_Hackathon/assets/84397275/e782b97b-aa00-456a-b0ad-bdeea2cdfa27)

![image](https://github.com/SandhyaRakhunde/TechForGood_Hackathon/assets/84397275/6cd8cd1a-04b3-4efa-88e7-f2c6176da45c)

![image](https://github.com/SandhyaRakhunde/TechForGood_Hackathon/assets/84397275/dc96bd2f-16c0-4829-922f-2ef407efc38c)

![image](https://github.com/SandhyaRakhunde/TechForGood_Hackathon/assets/84397275/ac3863d8-c310-4aa4-82c9-9cae8382a33c)



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

## 🚀 Getting Started

To run the Saksham Gram Mahila application on your local machine, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/saksham-gram-mahila.git`
2. Install dependencies: `cd saksham-gram-mahila && npm install`
3. Set up the database: Ensure MongoDB is installed and running. Create a `.env` file and add your database connection string.
4. Start the server: `npm start`
5. Open `http://localhost:5000` in your web browser.


 
 
