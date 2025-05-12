## 🔧 GitHub Actions Deployment Workflow

This repository uses a GitHub Actions workflow to automatically build and deploy a Hugo static website to GitHub Pages.

### 🛠️ Workflow Overview

- **Trigger:** The workflow runs on every push to the `main` branch.
- **Steps:**
  1. **Checkout:** Clones the source code and submodules.
  2. **Setup Hugo:** Installs Hugo version 0.144.1 with extended features enabled.
  3. **Build Site:** Builds the static files with `hugo -D --gc --minify`.
  4. **Deploy:** Publishes the generated site to the `gh-pages` branch using `peaceiris/actions-gh-pages`.

### 🤖 Workflow File

The workflow configuration file is located at `.github/workflows/gh-pages-deployment.yaml`.

### 📄 Claude Explanation

For a detailed, line-by-line explanation of the workflow, see [github-actions-workflow-explanation.pdf](github-actions-workflow-explanation.pdf). This file contains a conversation with Claude that explains how each part of the workflow functions.

### 🌐 Deployed Site

You can view the live deployed site here:  
`https://<your-github-username>.github.io/hugo-mock-landing-page-autodeployed/`




# 🚀 ConexUs - Smart Contact Manager  

**ConexUs** is a modern, AI-powered contact management tool designed to help you maintain and strengthen relationships effortlessly.  



## Some Main Features:
✅ **Smart Reminders** – Get automatic notifications to stay in touch with contacts  
✅ **AI-Powered Meeting Prep** – AI-generated conversation summaries & talking points  
✅ **Voice Memo to Notes** – Convert voice memos into structured text  
✅ **Calendar Syncing** – Automatically updates last-met dates from your calendar  
✅ **Important Date Reminders** – Never forget birthdays or work anniversaries  

## Setup & Development  
To run this project locally:  
1. **Clone the repository:**  
   ```sh
   git clone https://github.com/etwitmyer/hugo-mock-landing-page.git
