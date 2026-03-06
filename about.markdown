---
layout: page
title: About
permalink: /about/
---

# How to Install Jekyll on Windows

### 1. Install Ruby
First you need to install **Ruby** on your device.

Website:  
https://rubyinstaller.org/downloads/

### 2. Run the Installer
Run the Ruby installer. It will open automatically.  
Just go through all **three steps** of the installation.  
This might take a few minutes.

### 3. Install Jekyll
After the installation is finished, open **Command Prompt (cmd)** or **PowerShell** and type:

```powershell
gem install jekyll
```

Then press **Enter**.

### 4. Done
Jekyll is now installed on your system.

---

# How to Create a Website with Jekyll

### 1. Create the GitHub Repository
First create a **GitHub Pages repository** using the guide that was provided.

Guide:
https://docs.github.com/en/pages/quickstart 

### 2. Clone the Repository
Clone the repository locally to your computer.

Example:

```powershell
git clone https://github.com/yourusername/yourrepo.git
```

### 3. Create the Jekyll Site
Open **Command Prompt (cmd)** or **PowerShell** and navigate into your repository folder.

Then run:

```powershell
cd yourreponame
jekyll new .
```

The `.` means the site will be created **inside the current folder**.

### 4. Project Files
After running the command, Jekyll creates the necessary folders and files, for example:

- `_config.yml`
- `index.md`
- `_posts`
- `Gemfile`

### 5. Test the Website
To start the local server, run:

```powershell
bundle exec jekyll serve
```

Then open your browser and go to:

```
http://localhost:4000
```

Your Jekyll website should now be running locally.