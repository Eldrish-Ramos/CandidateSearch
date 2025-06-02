# Refined Candidate Search

A React + TypeScript application that allows employers to search for and save potential candidates using the GitHub API.

## Features

- Search for random GitHub users as potential candidates.
- View candidate details: name, username, avatar, location, email, company, and GitHub profile.
- Save promising candidates to a persistent list (localStorage).
- Reject candidates and move to the next one.
- View and manage your saved candidates.
- Responsive and modern UI.

## Getting Started

### Prerequisites

- Node.js (v16+ recommended)
- npm

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/refined-candidate-search.git
   cd refined-candidate-search
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Set up your GitHub API token:**
   - Create a [GitHub Personal Access Token](https://github.com/settings/tokens) (no extra permissions needed).
   - Copy `.env.EXAMPLE` to `.env` in the `environment` folder and add your token:
     ```
     VITE_GITHUB_TOKEN=your_github_token_here
     ```

4. **Start the development server:**
   ```sh
   npm run dev
   ```

5. **Open your browser:**  
   Visit [http://localhost:5173](http://localhost:5173) (or the port shown in your terminal).

## Usage

- **Home:** Browse random GitHub users. Save or reject candidates.
- **Saved Candidates:** View your saved candidates and remove any if needed.

## Project Structure

- `src/` - Main source code
  - `components/` - Reusable UI components
  - `pages/` - Main application pages
  - `api/` - GitHub API interaction
  - `utils/` - Utility functions (e.g., localStorage)
  - `interfaces/` - TypeScript interfaces

## Deployment

You can deploy this app to [Render](https://render.com/) or any static hosting provider.  
Set the `VITE_GITHUB_TOKEN` environment variable in your deployment settings.

## License

MIT License

---

© 2025 Your Name
