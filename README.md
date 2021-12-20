**Easy to set up React and Express apps that run simultaneously.**   
*Inspired and done by tutorial of Brad Traversy @TraversyMedia*

*Steps:*   
1: Clone the repo or download it as a zip file.    
2: Open a terminal in the containing folder.    
3: Type in: **npm install**  -  *This will install all dependecies for Express.*   
4: Type in: **npm run client-install**  -  *This will install all dependencies for the React app.*   
5: Type in: **npm run dev**  -  *This will run both apps simultaneously using concurrently.*

**If you want to run the server Only:**   
Type in: **npm run server**  -  *Nodemon is used, so no restarts of the server needed when changes are made.*

**If you want to run the client only:**   
Type in: **npm run client**

*The srver is running on process.env.port || 5000 and the client is on port 3000*
