# Enem Specialist

## Project Documentation

### Architecture
This project follows a modular architecture pattern, comprised of several components designed to handle specific features efficiently. The architecture includes:

- **Frontend**: Built with React, responsible for the user interface.
- **Backend**: Node.js and Express.js based server handling API requests.
- **Database**: MongoDB for data persistence.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/luizguilhermevalentinecreis-ai/enem-specialist.git
   cd enem-specialist
   ```
2. Install dependencies:
   - For the backend:
     ```bash
     cd backend
     npm install
     ```
   - For the frontend:
     ```bash
     cd frontend
     npm install
     ```

3. Configure environment variables in a `.env` file for backend configuration.

4. Start the services:
   - In one terminal, run:
     ```bash
     cd backend
     npm start
     ```
   - In another terminal, run:
     ```bash
     cd frontend
     npm start
     ```

### Features
- Comprehensive question bank for ENEM exams.
- User-friendly interface for practice tests.
- Performance tracking and progress analysis.

### Usage Instructions
Once the application is running:

1. Navigate to `http://localhost:3000` in your web browser.
2. Create an account or log in to start practicing.
3. Select a test from the available question bank to begin.

### License
This project is licensed under the MIT License.