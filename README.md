# node-chat_file_login
* Brief introduction of implemented functions
1. Login function. Login is done through session, and session is deleted when logging out.
2. File upload function. Save the file for each ID through db. (The file is saved even after logout and refresh).
   Click on the name to run the file.
3. Chat function. It provides broad cast type chat through soket.io.

how Build an environment for execution
1.Install node.js (https://nodejs.org/en/download/)
2. Editor installation .
3. Install mongoDB (https://www.mongodb.com/download-center?jmp=nav#community)
4. Install this compressed file codigmInternTask (https://github.com/manjoong/codigm)

* How to run (windows)
0. Create a folder to store db (db storage)
1. Open the cmd window, move from the installed MongoDB folder to the bin folder and run'mongod --dbpath [designated path (db storage)]'.
2. Unpack the'int222-myproject' archive.
3. Go to the extracted'int222-myproject' folder through the'cmd' window.
4. Enter'npm install' in the moved'cmd' window
5. Enter'node app.js' in the'cmd' window (check the'Connection Completed!' console if connected normally).
6. Open the Internet address bar and search for'localhost:3003'.
7. Go to the main page.
