# CMS Frontend

This repository contains the frontend applications for our Content Management System (CMS) project.

## Project Structure

This repository is organized into two main projects:

1. **Promo Site**: A Next.js 14 application serving as the public-facing website.
2. **Admin Dashboard**: A React 18+ application built with Vite, providing the CMS administration interface.

## Getting Started

### Prerequisites

- Node.js (v18 or later)
- npm or yarn

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/your-organization/cms-frontend.git
   cd cms-frontend
   ```

2. Install dependencies for both projects:
   ```
   cd promo-site
   npm install
   cd ../admin-dashboard
   npm install
   ```

### Running the Applications

#### Promo Site (Next.js)

```
cd promo-site
npm run dev
```

The promo site will be available at `http://localhost:3000`.

#### Admin Dashboard (React + Vite)

```
cd admin-dashboard
npm run dev
```

The admin dashboard will be available at `http://localhost:5173`.

## Development

- Follow the coding standards and guidelines outlined in our project documentation.
- Write unit tests for new components and features.
- Ensure responsive design and cross-browser compatibility.

## Building for Production

### Promo Site

```
cd promo-site
npm run build
```

### Admin Dashboard

```
cd admin-dashboard
npm run build
```

## Contributing

Please read our CONTRIBUTING.md file for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
