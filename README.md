# Interactive College Campus Blueprint
A complete, professional, and mobile-friendly interactive digital map based on the official college SVG blueprint.
This project is engineered as a highly optimized **Single-Page Application (SPA)** contained within index.html. This means you do **not** need to manage 30 different HTML files. Every building has its own view and URL link, but all the data is managed from one simple configuration section at the top of the code!
## 📂 GitHub Repository Folder Structure
To prepare this project for GitHub Pages, set up your repository with this exact structure:
```text
your-github-repo-name/
│
├── index.html           <-- (The single HTML code provided above)
├── README.md            <-- (This file)
│
└── assets/
    └── images/          <-- (Create these folders to store your photos)
        ├── main-bldg-gf.jpg
        ├── lib-main.jpg
        └── ...

```
## 📷 How to Add Building Photographs
 1. Take or find a photo of a building (e.g., the Main Library).
 2. Save it as a .jpg file.
 3. Name the file to match the building ID from the configuration (e.g., lib-main.jpg).
 4. Upload it to your GitHub repository inside the **assets/images/** folder.
*Note: If you don't upload a photo for a specific building, the website is smart enough to display a sleek, professional "Photograph Not Uploaded Yet" placeholder automatically!*
## 📝 How to Edit Website Information
All text, links, and building information can be edited directly inside index.html without needing to understand complex HTML or CSS.
 1. Open index.html in the GitHub editor.
 2. Scroll to the very bottom to find the **JAVASCRIPT LOGIC & CONFIGURATION** section.
 3. Edit SITE_CONFIG to change the main details:
   ```javascript
   const SITE_CONFIG = {
       collegeName: "YOUR COLLEGE NAME",
       instagramLink: "[https://instagram.com/priyabrat_handle](https://instagram.com/priyabrat_handle)" 
   };
   
   ```
 4. Scroll down to the BUILDINGS dictionary to edit individual building information:
   ```javascript
   "lib-main": {
       title: "Main Library",
       image: "./assets/images/lib-main.jpg",
       about: "Type your new paragraph about the library here.",
       departments: "Library Science",
       facilities: "Type the facilities here."
   },
   
   ```
## 🚀 How to Publish using GitHub Pages
Follow these step-by-step instructions to make your website live on the internet:
 1. **Create Repository:** Go to GitHub and create a new public repository (e.g., college-map).
 2. **Upload Files:** Upload index.html and your assets/images/ folder to the repository.
 3. **Open Settings:** Click the **Settings** gear icon at the top of your GitHub repository.
 4. **Go to Pages:** On the left sidebar menu, click on **Pages**.
 5. **Select Branch:** Under the "Build and deployment" section, look for the "Branch" dropdown. Change it from None to main (or master).
 6. **Save:** Click the **Save** button.
 7. **Wait:** Wait about 2 to 3 minutes for GitHub to build the site.
 8. **View Website:** Refresh the Pages settings screen. You will see a message at the top saying: *"Your site is live at https://[username].github.io/[repo-name]/"*. Click the link to view your live blueprint!
