# Adult Census Income Predictor

A modern, static web application that predicts whether an individual's annual income exceeds $50K based on census demographic data. 

This project was built with a premium, sleek Landio-inspired dark mode frontend design, perfectly tailored for high-conversion landing pages.

## Features
- **Modern UI/UX**: Built with vanilla HTML/CSS/JS, featuring a premium dark-mode theme, minimal borders, and high-contrast typography.
- **Dynamic Form Handling**: JavaScript intercepts form submissions, displays smooth loading states, and processes the mock prediction engine seamlessly without requiring a backend.
- **Fully Static Deployment**: Designed to run entirely in the browser, making it infinitely scalable and free to host.

## Project Structure
```
├── index.html           # Main frontend form
├── style.css            # Premium dark mode Landio styling
├── script.js            # Form handling and mock prediction logic
└── README.md            # Documentation
```

## Deployment (GitHub Pages)

This project is fully structured for instant deployment on GitHub Pages:
1. Go to your repository **Settings** on GitHub.
2. Navigate to **Pages** on the left sidebar.
3. Under **Build and deployment**, set the **Source** to `Deploy from a branch`.
4. Select the `main` branch and `/ (root)` folder, then click **Save**.
5. Your premium web form is now live globally!

## Testing Locally

To test the frontend locally:
- Simply double-click the `index.html` file to open it in your web browser. No server is required.

## Extending the App
If you wish to integrate a real Machine Learning model in the future, you can easily wire the frontend `fetch` request in `script.js` to a Python Serverless Function (e.g. using Vercel or AWS Lambda).
