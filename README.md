# Receipt Submission Form (Angular + Node.js API)

## Overview

This project is a standalone receipt submission form built using Angular 17 and a lightweight Node.js backend. It simulates a form submission flow for internal use cases such as business receipt tracking. The application demonstrates client-server communication, form validation, API interaction, and modular component architecture.

---

## Technologies Used

- Angular 17 (Standalone Component API)
- TypeScript
- HTML5 & CSS3
- Node.js & Express (REST API)
- HttpClientModule (Angular)
- Visual Studio Code
- JSON data handling

---

## Features

- Responsive Angular form using `ngModel` and `FormsModule`
- Form validation with real-time feedback (disables submit button unless form is valid)
- POST submission to an Express backend API (`/api/receipts`)
- Console logging of submission result
- Fully decoupled frontend and backend logic
- Simple REST API built with Node.js for data handling

---

## How to Run

### Prerequisites

- [Node.js](https://nodejs.org/) installed
- Angular CLI installed  
  ```bash
  npm install -g @angular/cli
