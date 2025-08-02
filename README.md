# Mini DevOps App
This is a simple Node.js app created as a hands-on mini project to understand the fundamentals of DevOps, especially CI/CD using GitHub Actions.

🔧 Technologies Used
- Node.js
- Git & GitHub
- GitHub Actions

 📦 Features
- CI/CD pipeline using GitHub Actions
- Test automation on every push to `main`
- Runs a basic Node.js app on `localhost:3000`
- Clean, minimal structure for DevOps beginners

 📁 Project Structure
mini-devops-app/
├── .github/
│ └── workflows/
│ └── ci.yml # GitHub Actions workflow
├── index.js # Main app file
├── package.json # Project metadata and scripts
└── README.md # Project documentation

1. Clone the repository
git clone https://github.com/mahamtahirx/mini-devops-app.git

  cd mini-devops-app

3. Install dependencies
   
   npm install

5. Start the application
 
   npm start

6. Run tests

   npm test

By default, the app runs at:
🌐 http://localhost:3000. 
If everything works, the terminal will say:

   "Test passed!"

💡 Why this project?
This mini app is part of my DevOps learning journey — understanding the essential role Git, GitHub, and automation pipelines play in modern software development. A small step, but a strong foundation toward mastering CI/CD.






