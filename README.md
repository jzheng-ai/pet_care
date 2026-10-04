# Wag & Wash

A responsive, single-file homepage for a fictional pet cleaning shop.

## View the homepage

Open `index.html` in a web browser. CSS, JavaScript, and the main photo are embedded, so no installation or build is required.

## Features

- Responsive desktop and mobile layouts
- Service cards with illustrative prices
- Expandable FAQs
- A visit planner that creates a summary without sending or reserving an appointment

## Upload to GitHub

1. Create an empty repository named `pet_care` at https://github.com/new. Choose your preferred visibility. Do not add a README, .gitignore, or license there because this project already has local files.
2. In PowerShell, run the commands below, replacing the name, email, and GitHub username with your own values. The Git identity settings apply only to this project.

```powershell
cd C:\Users\Jane\Desktop\pet_care
git config user.name "Your Name"
git config user.email "your-email@example.com"
git add index.html README.md .gitignore
git commit -m "Create pet cleaning shop homepage"
git remote add origin https://github.com/YOUR-USERNAME/pet_care.git
git push -u origin main
```

If the initial commit already exists, skip the `git add` and `git commit` commands. Follow any GitHub authentication prompt when pushing. Never put your password or access token in the remote URL.

For later updates:

```powershell
git add index.html README.md .gitignore
git commit -m "Update homepage"
git push
```

Uploading the repository stores the source on GitHub; it does not automatically publish a live website.

## Photo

The embedded photo was obtained from [Time for Paws](https://www.timeforpaws.co.uk/blogs/articles/a-guide-to-grooming-your-dog). No license for that third-party photo is granted by this repository.
