
### Steps to Run the Project

#### 1. Clone the Repository

```bash
git clone <repository-url>
cd <project-folder>
```

#### 2. Install Backend Dependencies

Navigate to the backend folder (usually named `server`, `backend`, or similar):

```bash
cd backend
npm install
```

#### 3. Set Up Environment Variables

Create a `.env` file in the backend folder and add your environment variables:

```
PORT=5000
MONGODB_URI=mongodb://localhost:27017/your-database-name
JWT_SECRET=your-secret-key
```

#### 4. Start the Backend Server

```bash
npm start
```
or for development:
```bash
npm run dev
```

#### 5. Install Frontend Dependencies

Navigate to the frontend folder (usually named `client`, `frontend`, or similar):

```bash
cd ../client
npm install
```

#### 6. Start the Frontend

```bash
npm start
```

***

### Project Structure

- `backend/` – Node.js and Express server, API routes, MongoDB connection
- `client/` – React frontend, UI components, API calls

***

### Running Both Backend and Frontend Together

If you want to run both simultaneously, use a tool like `concurrently`:

In the project root:
```bash
npm install concurrently --save-dev
```

Add a script to your root `package.json`:
```json
"scripts": {
  "start": "concurrently \"npm --prefix backend start\" \"npm --prefix client start\""
}
```

Then run:
```bash
npm start
```
