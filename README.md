## Getting Started

Welcome to the VS Code Java world. Here is a guideline to help you get started to write Java code in Visual Studio Code.

## Folder Structure

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources
- `lib`: the folder to maintain dependencies

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

> If you want to customize the folder structure, open `.vscode/settings.json` and update the related settings there.

## Dependency Management

The `JAVA PROJECTS` view allows you to manage your dependencies. More details can be found [here](https://github.com/microsoft/vscode-java-dependency#manage-dependencies).

---

## Web project notes

- This workspace contains a small static website (landing + gallery) in the project root.
- Auth: the project supports local admin login and optional Google Sign-In by providing a **Google Client ID** in the UI (Footer → Usuario → Configurar Google Client ID).
- The EmailJS/OTP feature was removed per request; only Google Client ID is supported for third-party auth.

### Mobile improvements

- The site now includes responsive CSS to work well on phones: footer stacks, gallery displays 1 item per view on small screens, and the 'Usuario' menu becomes a bottom sheet for easy touch access.
- Modals and panels use full-screen on small devices for improved usability.
To publish to GitHub:
1. Initialize a repo locally (already done) and push to your GitHub remote: git remote add origin <your-repo-url> ; git push -u origin main
2. Configure Google Cloud OAuth Client ID for the domain where you host the site.
