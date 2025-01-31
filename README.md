# HNG Stage 0 Task - Public API

This is a simple public API developed as part of the HNG Stage 0 Task. The API returns basic information in JSON format, including the user's registered email address, the current datetime in ISO 8601 format, and the GitHub URL of the project's codebase.

## Table of Contents
- [Requirements](#requirements)
- [Setup Instructions](#setup-instructions)
- [API Documentation](#api-documentation)
  - [Endpoint](#endpoint)
  - [Response Format](#response-format)
- [Deployment](#deployment)
- [Backlink](#backlink)

---

## Requirements
To run this project, you need the following:
- **Node.js** (v16 or higher)
- **npm** (Node Package Manager)
- **Express** (Web framework for Node.js)
- **CORS** (Middleware to handle Cross-Origin Resource Sharing)

---

## Setup Instructions
Follow these steps to set up and run the project locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/anajembaedwin/hng-stage0-task
   ```

2. **Navigate to the project directory:**
   ```bash
   cd hng-stage0-task
   ```

3. **Install dependencies:**
   ```bash
   npm install
   ```

4. **Start the server:**
   ```bash
   npm start
   ```

5. **Test the API:**
   Open your browser or use a tool like [Postman](https://www.postman.com/) and visit:
   ```
   http://localhost:3000
   ```

---

## API Documentation

### Endpoint
- **GET** `/`

### Response Format
The API returns a JSON response with the following fields:
- `email`: The registered email address used for HNG Slack workspace.
- `current_datetime`: The current datetime in ISO 8601 format (UTC).
- `github_url`: The GitHub URL of the project's codebase.

#### Example Response
```json
{
  "email": "anajembaedwin@gmail.com",
  "current_datetime": "2025-01-30T09:30:00Z",
  "github_url": "https://github.com/anajembaedwin/hng-stage0-task",
}
```

---

## Deployment
The API is deployed to a publicly accessible endpoint using [Render](https://render.com). You can access the live API here:

**Live API URL:** [https://hng-stage0-task.onrender.com](https://hng-stage0-task.onrender.com)

---

## Backlink
- [HNG Hire Node.js Developers](https://hng.tech/hire/nodejs-developers)

---

## License
This project is open-source and available under the [MIT License](LICENSE).

---

## Author
- **Edwin Anajemba**  
  GitHub: [anajembaedwin](https://github.com/anajembaedwin)  
  Email: anajembaedwin@gmail.com