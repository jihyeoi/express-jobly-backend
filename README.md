# Jobly
Jobly is a job board application built using Express.js, PostgreSQL, and Node.js. This application allows users to browse job listings, apply for jobs, and manage their profiles. Admin users can manage job listings and companies.

## Features
- User authentication and registration
- Browse and search for jobs and companies
- Apply for jobs
- Admin functionalities to manage jobs and companies

## Technologies Used
- Express.js
- PostgreSQL
- JSON Web Tokens (JWT) for authentication
- bcrypt for password hashing
- jsonschema for validation

## Installation
1. **Clone the repository**
   ```bash
   git clone https://github.com/jihyeoi/jobly.git
   cd jobly
   ```
2. **Install Dependencies**
   ```bash
   npm install
   ```
3. ***Set up the PostgreSQL database***
  ```bash
  createdb jobly
  createdb jobly_test
  ```
