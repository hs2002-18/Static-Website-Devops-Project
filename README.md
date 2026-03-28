# 🚀 Static Website DevOps Project


## 📖 Overview

This repository demonstrates a foundational project for deploying a static website using DevOps principles. It comprises a basic HTML, CSS, and JavaScript website, integrated with a Continuous Integration/Continuous Deployment (CI/CD) pipeline managed by GitHub Actions. The primary goal is to showcase the automation of building (if any pre-processing) and deploying static web content efficiently, ensuring rapid and reliable updates.

## ✨ Features

-   **Static Website Foundation**: A simple, clean HTML, CSS, and JavaScript based website.
-   **Automated Deployment**: Seamless deployment of the static content via GitHub Actions.
-   **Continuous Integration**: Automated checks and build processes (if applicable) triggered on every push.
-   **Scalable Hosting**: Ready for deployment to various static site hosting services (e.g., GitHub Pages, Netlify, Vercel, AWS S3).
-   **Clear Project Structure**: Organized directories for easy navigation and maintenance.

## 🛠️ Tech Stack

**Frontend:**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**DevOps:**

![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

## 🚀 Quick Start

To get this static website up and running locally or to understand its deployment process, follow these steps.

### Prerequisites

-   A modern web browser.
-   Git installed on your system.
-   (Optional) A local HTTP server for serving files (e.g., Python's `http.server`, `npm install -g http-server`).

### Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/hs2002-18/Static-Website-Devops-Project.git
    cd Static-Website-Devops-Project
    ```

2.  **View the website locally**
    You can open the `index.html` file directly in your browser:
    ```bash
    open index.html # On macOS
    # or navigate to the file in your file explorer
    ```
    Alternatively, use a local HTTP server for a more realistic environment (e.g., to handle relative paths correctly):
    ```bash
    # Using Python's built-in server (if Python is installed)
    python -m http.server 8000

    # Or using http-server (if installed via npm)
    http-server -p 8000
    ```

3.  **Open your browser**
    If using a local server, visit `http://localhost:8000`.

## 📁 Project Structure

```
Static-Website-Devops-Project/
├── .github/              # GitHub Actions workflows for CI/CD
│   └── workflows/        # Contains specific workflow definitions
├── css/                  # Directory for all CSS stylesheets
│   └── [styles.css]      # Example stylesheet
├── js/                   # Directory for all JavaScript files
│   └── [script.js]       # Example JavaScript file
├── index.html            # The main entry point of the static website
└── README.md             # Project documentation (this file)
```

## 🔧 Development

Development involves directly editing the HTML, CSS, and JavaScript files.

### HTML
-   Modify `index.html` to update the structure and content of the website.

### CSS
-   Edit files within the `css/` directory to change the website's styling.

### JavaScript
-   Add or modify scripts in the `js/` directory to enhance interactivity.

No specific build tools are required as this is a vanilla static site.

## 🚀 Deployment

This project is set up for automated deployment using GitHub Actions.

### GitHub Actions Workflow

The `.github/workflows/` directory contains the CI/CD pipeline. Pushes to the `master` branch will trigger a workflow that:
1.  **Checks out the code**.
2.  **Deploys the static website**. (Specific deployment target inferred to be GitHub Pages based on typical use cases for such a project and a live demo link).

### How to Trigger Deployment

-   Simply push your changes to the `master` branch of this repository.
-   GitHub Actions will automatically pick up the changes, run the defined workflow, and deploy the updated static website.
-   Monitor the progress and status of your deployments under the "Actions" tab in your GitHub repository.

## 🤝 Author
Harsh Shrimali


</div>

