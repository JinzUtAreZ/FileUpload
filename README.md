# Edit Settings.json

1. Enable emmet in visual code
   click setting -> command pallete -> (keyword _settings json_)
   input code: "emmet.includeLanguages": {
   "javascript": "javascriptreact"
   }

# Install node modules

1. set to root folder and type in terminal
   npm install
2. set to client folder
   cd client
   npm install
3. remember server and client packages are separated node modules.

# Initialize Server Project

1. npm init -y ---> create package.json file
2. npm i express express-fileupload
3. npm i -D nodemon concurrently ----> install running server (nodemon)
   install proxy server (concurrently)

# Initialize Client Project

4. npx create-react-app client ----> create folder with react components
   remove serviceworker.js, logo.svg, index.css, app.test.js
5. add proxy in package.json (react components)
   "proxy": "http://localhost:3001"
6. cd client (react components) npm i axios (fetch data) cd .. (go to root folder)

# Additional

1. get bootstrap grab the css link and js files

     <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
     paste in public/index.html header for design purposes.

     <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
   <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
   <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>

#Website References to check

article https://codeforgeek.com/multiple-file-upload-node-js/ multiple upload
watch https://www.youtube.com/watch?v=3f5Q9wDePzY mongodb,multer upload
