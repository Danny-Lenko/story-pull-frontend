# CMS Frontend

This repository contains the frontend applications for the StoryPull (CMS) project.

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

## Git Flow Workflow
1. Create the develop branch: This branch will be used for ongoing development work. A develop branch is created from the main branch.
2. Create feature branches: When starting work on a new feature or bug fix, create a new feature branch from the develop branch.
3. Develop and merge the feature branch into develop: Make any necessary changes to your local code on the feature branch. Once the feature is complete and tested, merge the branch back into the develop branch.
4. Create the release branch: When it’s time to prepare a new release, create a new release branch from the develop branch with a descriptive name that includes the version number, for example, release/1.0. Test the release thoroughly to catch any bugs or issues to ensure it’s production-ready.
5. Merge the release branch into main: Once the release is ready, merge the release branch into the main branch and tag it with a version number. Use a pull request to ensure code reviews and approval from other team members.
6. Repeat the process: Once the release is complete, switch back to the develop branch and start the process over again with a new feature branch.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
