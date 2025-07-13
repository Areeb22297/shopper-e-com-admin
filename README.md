# Shopper E-Commerce Admin Panel

Admin dashboard for managing products and monitoring activity in the Shopper full-stack e-commerce platform.

## Features

- Add, edit, and remove products
- View product listings and details
- Manage product categories
- Dashboard overview

## Tech Stack

- **Frontend:** React
- **Routing:** React Router
- **Backend API:** [Shopper E-Com Backend](../shopper-e-com-backend)
- **State Management:** Local state

## Getting Started

### Prerequisites

- Node.js (>=14)
- npm

### Installation

```bash
git clone https://github.com/Areeb22297/shopper-e-com-admin.git
cd shopper-e-com-admin
npm install
```

### Running the App

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Configuration

- Backend API endpoint is set in `src/App.js`:
  ```
  export const backend_url = 'https://shopper-e-com-backend.up.railway.app';
  ```
- Currency is set to INR (`₹`).

## Folder Structure

- `src/Components`: UI components (Navbar, Footer, etc.)
- `src/Pages`: Main admin dashboard
- `src/App.js`: Main app and routing
- `src/index.js`: Entry point

## Usage

- Log in as admin
- Add, edit, or remove products
- View dashboard and product listings

## License

MIT

## Acknowledgements

- [Create React App](https://github.com/facebook/create-react-app)
This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
