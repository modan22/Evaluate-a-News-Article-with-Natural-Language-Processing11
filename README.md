

# Evaluate A News Article with Natural Language Processing

## Tools Used
* HTML
* CSS
* JavaScript
* Node.js
* Express
* Webpack
* MeaningCloud API
* Jest
* Workbox

## Setup Instructions

1. **Check Node.js and npm**
   Verify that Node.js and npm are installed by running:
   ```bash
   node -v
   npm -v
   ```

2. **Navigate to the Project Directory**
   Move to your project folder:
   ```bash
   cd <project directory>
   ```

3. **Clone the Repository**
   Retrieve the project repository:
   ```bash
   git clone <repo>
   ```

4. **Install Project Dependencies**
   Install required npm packages:
   ```bash
   npm install
   ```

5. **Install Webpack Loaders and Plugins**
   Add the necessary tools for development:
   ```bash
   # Babel for JavaScript transpiling
   npm install --save-dev @babel/core @babel/preset-env babel-loader

   # CSS and Sass processing
   npm install --save-dev style-loader node-sass css-loader sass-loader

   # Webpack plugins for optimization and management
   npm install --save-dev clean-webpack-plugin html-webpack-plugin mini-css-extract-plugin optimize-css-assets-webpack-plugin terser-webpack-plugin

   # Workbox for managing service workers
   npm install --save-dev workbox-webpack-plugin
   ```

6. **Obtain a MeaningCloud API Key**
   Register at [MeaningCloud](https://www.meaningcloud.com/developer/create-account) to get your API key.

7. **Configure Environment Variables**
   1. Install the `dotenv` package:
      ```bash
      npm install dotenv
      ```

   2. Create a `.env` file in the project root and insert your API key:
      ```env
      API_KEY=**************************
      ```

8. **Build and Run the Project**

   | Command            | Purpose           |
   |--------------------|-------------------|
   | `npm run build-prod` | Build the application |
   | `npm start`        | Launch the application |

9. **Access the Application**
   Open your web browser and visit [http://localhost:8081/](http://localhost:8081/).

---

This version maintains the clarity and structure of your setup instructions while offering a fresh rephrasing.
