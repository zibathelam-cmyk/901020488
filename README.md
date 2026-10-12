# Community Library Management System

A React-based community library app created for the Web Application Development assignment.

## Features
- Dashboard with book totals, available copies, registered members, and low-stock alerts.
- Book management: add, edit, search, and delete books.
- Stock transactions: add stock or record borrowing, with transaction history.
- User management: add, edit, and delete users.
- Login form and role-based admin controls.
- React Router navigation.
- Persistent browser Local Storage.
- Responsive layout for desktop and mobile.

## Requirements
Install Node.js LTS and Visual Studio Code.

## Run the project
Open this project folder in VS Code, then choose **Terminal → New Terminal** and run:

```bash
npm install
npm run dev
```

Open the local URL printed in the terminal (usually `http://localhost:5173`).

To check a production build:

```bash
npm run build
```

## Demo login
- Membership ID: `ADMIN001`
- Password: `library123`

The demo login is intended for coursework demonstration only. This app stores data in the browser and does not provide secure production authentication.

## Notes
- Data is saved in the browser's Local Storage on the same browser/device.
- Use the **Reset demo data** button on the Users page to restore sample data.
- For a real deployment, replace demo authentication and Local Storage with a secure backend and database.
