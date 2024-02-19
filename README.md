## Setup
1. Ensure you have Node.js above 18.x installed, install Vue CLI and Serve
   ```
   sudo yarn global add @vue/cli serve
   ```
2. Goto the test frondend project, then host the build bundle locally.
   ```
   cd ClientApp/hello-world
   ```
   Setup dependencies
   ```
   yarn
   ```
   Build and host the frontend application locally
   ```
   yarn build
   cd dist
   serve
   ```
4. Frontend application will be running on port 3000.
5. **Run/Debug** the ASP.NET application in Rider, access `http://localhost:5225`, compare the page loading latence in Incognito window.
