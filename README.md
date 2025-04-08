# Receipt Submission Form (Angular + Node.js API)

## Overview
This project is a standalone receipt submission form built using Angular 17 and a lightweight Node.js backend. It simulates a form submission flow for internal use cases such as business receipt tracking. The application demonstrates client-server communication, form validation, API interaction, and modular component architecture.

## Technologies Used
- Angular 17 (Standalone Component API)
- TypeScript
- HTML5 & CSS3
- Node.js & Express (REST API)
- HttpClientModule (Angular)
- Visual Studio Code
- JSON data handling

## Features
- Responsive Angular form using `ngModel` and `FormsModule`
- Real-time form validation with disabled submit button until form is valid
- POST submission to an Express backend API (`/api/receipts`)
- Console and network logging of submission result
- Decoupled frontend and backend logic
- Simple REST API built with Node.js

## How to Run

### Backend Setup
1. Navigate to the root project directory
2. Install dependencies:
   ```bash
   npm install express cors
   
3. Start the backend server:
   node server.js

4. Server will run on: http://localhost:5000

### Frontend Setup
1. Navigate to the frontend/ directory

2. Install dependencies:
   npm install

3. Start the Angular development server:
   ng serve

4. Open browser at: http://localhost:4200 (or alternate port if prompted)

Folder Structure

receipt-submission-app/
├── frontend/
│   ├── src/
│   ├── angular.json
│   └── package.json
├── backend/
│   └── server.js
├── screenshots/
│   ├── 01-form-empty.png
│   ├── 02-form-filled.png
│   ├── 03-network-success.png
│   ├── 04-terminal-log.png
│   └── 05-form-validation.png
└── README.md
