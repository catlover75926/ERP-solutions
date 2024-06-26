1. **Check if you have Node.js installed in your system**

   run

   ```bash
    node -v
   ```

   - If it outputs a version number thats <= `18`, we're good to go.
   - If it throws an error, it means you dont have Nodejs installed in your system. [Get it from here](https://nodejs.org)

   > Bonus: Install `yarn` too for faster libs installation. [Refer this guide](https://classic.yarnpkg.com/lang/en/docs/install/#debian-stable)

2. **Install Dependancies**

   - If you prefer Yarn, run
     ```bash
     yarn
     ```
   - If you prefer Npm, run
     ```bash
     npm i
     ```

3. **Run Dev Server**
   - Yarn:
     ```bash
     yarn dev
     ```
   - Npm:
     ```bash
     npm run dev
     ```
