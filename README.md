```echo "# NpmLiteServerFrontEndApp" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/Microshaoft/NpmLiteServerFrontEndApp.git
git push -u origin master

npm init -y
npm i lite-server --save

npm start
```


```
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "lite-server"
  },
```