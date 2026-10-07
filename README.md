# AI Resume Builder

An AI-powered resume builder that helps users create, customize, preview, and export professional resumes through an intuitive web interface.

## 🚀 Overview

AI Resume Builder is a modern React application designed to simplify the resume creation process.

Users can build resumes using structured sections, enhance their content with AI-powered assistance, preview their resume in real time, and export the finished resume as a PDF.

The application combines a responsive user interface with authentication, AI generation, resume editing, and document export functionality.

## ✨ Features

* 🤖 **AI-Powered Resume Assistance**

  * Generate and improve resume content using Google's Generative AI.
  * Get assistance with professional descriptions and resume sections.

* 🔐 **User Authentication**

  * Secure authentication and user management with Clerk.

* 📝 **Resume Builder**

  * Create and edit resume sections through an interactive interface.
  * Manage professional information, experience, education, skills, and other resume details.

* 👀 **Live Resume Preview**

  * Preview resume changes while editing.

* 📄 **PDF Export**

  * Generate downloadable PDF versions of completed resumes.

* 🎨 **Responsive UI**

  * Modern interface built with React and Tailwind CSS.
  * Designed to work across desktop and mobile screen sizes.

* 🔗 **Client-Side Routing**

  * Application navigation powered by React Router.

## 🛠️ Tech Stack

### Frontend

* React 18
* Vite
* JavaScript
* React Router
* Tailwind CSS
* Radix UI
* Lucide React

### AI

* Google Generative AI

### Authentication

* Clerk

### HTTP & Utilities

* Axios
* UUID
* Sonner
* React Simple WYSIWYG

### Document Generation

* React to PDF

## 🏗️ Project Structure

```text
AI-Resume-Builder/
├── public/                 # Static assets
├── service/                # Application services
├── src/                    # React application source
├── .eslintrc.cjs           # ESLint configuration
├── components.json         # UI component configuration
├── index.html              # Application entry point
├── package.json            # Dependencies and scripts
├── tailwind.config.js      # Tailwind CSS configuration
├── vite.config.js          # Vite configuration
└── README.md               # Project documentation
```

## ⚙️ Getting Started

### Prerequisites

Make sure you have the following installed:

* Node.js
* npm

You can verify your installation with:

```bash
node --version
npm --version
```

### 1. Clone the repository

```bash
git clone https://github.com/devanshcodex/AI-Resume-Builder.git
cd AI-Resume-Builder
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a `.env` file in the project root and add the required API and authentication credentials.

Example:

```env
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
VITE_GOOGLE_AI_API_KEY=your_google_ai_api_key
```

> Do not commit real API keys, secrets, or credentials to GitHub.

Make sure your environment variable names match the variables used by the application.

### 4. Start the development server

```bash
npm run dev
```

The application will be available at the local URL displayed by Vite, usually:

```text
http://localhost:5173
```

## 📦 Available Scripts

| Command           | Description                  |
| ----------------- | ---------------------------- |
| `npm run dev`     | Start the development server |
| `npm run build`   | Create a production build    |
| `npm run preview` | Preview the production build |
| `npm run lint`    | Run ESLint                   |

## 🔒 Security

Never commit sensitive credentials to the repository.

Before pushing changes to GitHub, verify that:

* `.env` files are ignored by Git.
* API keys are not hardcoded in source files.
* Authentication secrets are not committed.
* Private credentials are not included in documentation or screenshots.

## 🎯 Project Goals

The goal of this project is to make professional resume creation faster and easier by combining traditional resume-building tools with AI-assisted content generation.

## 🚧 Future Improvements

Potential improvements include:

* Additional resume templates
* More AI-powered writing tools
* Resume scoring and feedback
* Job-description matching
* Improved PDF layouts
* Resume sharing through public links
* Additional customization options
* Improved accessibility
* Automated testing
* Production deployment

## 👨‍💻 Contribution

This project was developed collaboratively.

The repository represents my work and contribution to the AI Resume Builder project. It is maintained here as part of my development portfolio.

Contributions, suggestions, and improvements are welcome.

## 📄 License

This project currently does not specify a separate open-source license.

If you plan to distribute the project publicly as open source, add an appropriate license before doing so.
