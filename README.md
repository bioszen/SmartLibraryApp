# Smart Code Library

## Overview
Smart Code Library is a single-file web application for managing and organizing code snippets.

## Deployment to GitHub Pages

To deploy this application to GitHub Pages:

1.  **Create a Repository:** Create a new repository on GitHub.
2.  **Push Code:** Push the contents of this folder to the repository.
    ```bash
    git init
    git add .
    git commit -m "Initial commit"
    git branch -M main
    git remote add origin <YOUR_REPO_URL>
    git push -u origin main
    ```
3.  **Configure Pages:**
    *   Go to your repository **Settings**.
    *   Navigate to the **Pages** section (on the left sidebar).
    *   Under **Build and deployment** > **Source**, select **Deploy from a branch**.
    *   Under **Branch**, select `main` and `/ (root)`.
    *   Click **Save**.

Your app will be live at `https://<USERNAME>.github.io/<REPO_NAME>/`.

## Google Analytics Configuration

Google Analytics tracking has been integrated for:
*   Application Load (Page View)
*   Snippet Uploads (Add to Library)

The Google Analytics Measurement ID has been configured in `index.html`.

## Privacy

**Your Data is Yours.**
Smart Code Library stores all your snippets, collections, and configurations exclusively in your browser's **Local Storage (LocalStorage)**.
*   There are no backend servers.
*   There are no cloud databases.
*   The application only reads and organizes the information you save locally.
*   The only data sent externally is anonymous usage analytics to Google Analytics.
