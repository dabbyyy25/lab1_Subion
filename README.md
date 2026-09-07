 # Danica Rose Subion Portfolio

 A simple personal portfolio webpage for **Danica Rose Subion**, a 20-year-old third-year Bachelor of Science in Information Technology student at Cavite State University.

 The website has a minimalist, warm editorial design and introduces Danica's interests in reading, writing, and badminton.

 ## About Danica

 - **Name:** Danica Rose Subion
 - **Age:** 20 years old
 - **Course:** Bachelor of Science in Information Technology (BSIT)
 - **Year level:** Third year
 - **University:** Cavite State University
 - **Hobbies:** Reading, writing, and badminton

 ## Website Sections

 ### Hero section

 The opening section introduces Danica with the message “Hello, I'm Danica Rose” and a button that leads to the About section.

 ### About section

 This section explains that Danica is building her technology skills while learning, creating, and growing as a student.

 ### Hobbies section

 Three interactive cards describe Danica's hobbies:

 1. **Reading:** Exploring stories, ideas, and new perspectives.
 2. **Writing:** Turning thoughts and reflections into words.
 3. **Badminton:** Staying active, focused, and present on the court.

 ### Contact section

 The final section provides a link that returns visitors to the beginning of the page.

 ## Project Files

 | File | Purpose |
 | --- | --- |
 | `main.html` | Page structure, content, navigation, sections, and footer |
 | `style.css` | Colors, typography, layout, responsive design, and animations |
 | `script,js` | Mobile navigation, scroll behavior, and project-card reveal effects |
 | `README.md` | Project documentation and Git instructions |

 ## Design Features

 - Minimalist editorial layout
 - Warm paper background with sage and peach hobby cards
 - Responsive design for desktop and mobile screens
 - Smooth scrolling between sections
 - Responsive mobile navigation menu
 - Header styling that changes while scrolling
 - Hover and keyboard-focus effects on hobby cards
 - Scroll reveal animation for hobby cards
 - Reduced-motion support for accessibility

 ## How to View the Website

 This is a static webpage, so no server or package installation is required.

 1. Open the project folder in VS Code.
 2. Open `main.html` in a browser.
 3. For automatic browser refresh, use the Live Server extension in VS Code.

 The JavaScript file uses a comma in its filename: `script,js`. The HTML file references that exact filename, so it should not be renamed unless the script reference is updated as well.

 ## Git Setup and Commands

 The project uses Git for version control. The local branch is named `main`, and the GitHub remote is named `origin`.

 ### Check the repository status

 ```powershell
 git status --short --branch
 ```

 This shows the current branch and any modified, added, or untracked files.

 ### Check the GitHub remote

 ```powershell
 git remote -v
 ```

 The expected remote format is:

 ```text
 origin  https://github.com/dabbyyy25/lab1_Subion.git (fetch)
 origin  https://github.com/dabbyyy25/lab1_Subion.git (push)
 ```

 ### Add project files

 ```powershell
 git add main.html style.css script,js README.md
 ```

 To add every changed file in the project instead:

 ```powershell
 git add .
 ```

 ### Create a commit

 ```powershell
 git commit -m "Create Danica Rose Subion portfolio"
 ```

 ### Set the GitHub remote

 If the remote URL is incorrect, replace it with the repository URL copied from GitHub:

 ```powershell
 git remote set-url origin https://github.com/dabbyyy25/lab1_Subion.git
 ```

 ### Push the main branch

 The first push connects the local `main` branch to GitHub:

 ```powershell
 git push -u origin main
 ```

 After the upstream is set, future pushes can use:

 ```powershell
 git push
 ```

 ### Pull the latest changes

 ```powershell
 git pull origin main
 ```

 ### View commit history

 ```powershell
 git log --oneline -5
 ```

 ## GitHub Troubleshooting

 ### “The current branch main has no upstream branch”

 Run:

 ```powershell
 git push --set-upstream origin main
 ```

 This is the same as:

 ```powershell
 git push -u origin main
 ```

 ### “Repository not found”

 Confirm that:

 - The repository exists on GitHub.
 - The repository owner is `dabbyyy25`.
 - The repository is named exactly `lab1_Subion`.
 - You are signed in to the GitHub account that owns the repository.
 - The remote URL is correct.

 Check or update the remote with:

 ```powershell
 git remote -v
 git remote set-url origin https://github.com/dabbyyy25/lab1_Subion.git
 git push -u origin main
 ```

 If the repository has a different name or owner, replace those parts of the URL.

 ## Before Pushing

 `main.html` should contain only one complete HTML document. If merge-conflict text appears, remove the conflict markers and keep the intended version before committing:

 ```text
 <<<<<<< HEAD
 =======
 >>>>>>> branch-name
 ```

 Then check the file, stage the fix, commit it, and push:

 ```powershell
 git status
 git add main.html
 git commit -m "Resolve HTML merge conflict"
 git push
 ```

 ## License

 This is a personal student portfolio project created for learning and presentation purposes.
