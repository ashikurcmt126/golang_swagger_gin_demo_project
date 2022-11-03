**Step 1: Install Swag**
-
- _go get -u github.com/swaggo/swag/cmd/swag_
- _go get -u github.com/swaggo/gin-swagger_
- _go get -u github.com/swaggo/files_

**Step 2: Install Swag**
-
- _swag init_

After every 'swag init' command run, a new docs folder will be created.
Then browse http://localhost:8080/docs/index.html we will see the swagger 
documentation. 

If your main.go file is not in root but uses the models defined in root, you can provide the path of main.go file.
- swag init -d "./" -g "$FOLDER_NAME/main.go"

