## Setup
1. Ensure you have Node.js above 18.x installed, install Vue CLI
   ```
   sudo yarn global add @vue/cli
   ```
2. Goto the test frondend project, then host the build bundle locally.
   ```
   cd ClientApp/hello-world
   ```
   ```
   yarn host
   ```
3. Frontend application will be running on port 3000.
4. **Run/Debug** the ASP.NET application in Rider, access `http://localhost:5225`, compare the page loading latence in Incognito window.
