# Sample Node.js Project

A Node.js project written using Express. EJS was used as the view engine.

# Node JS version - Install these softwares


```sh
node --version
v14.21.3

npm --version
6.14.18
```

# ManualInstallation

You need to write the following commands on the terminal screen so that you can run the project locally.

```sh
1. git clone https://github.com/ashithss/docker-nodejs.git
2. cd docker-nodejs
3. npm install
4. npm start
5. The application is running on [localhost](http://localhost:3005).
```

# To test docker image - Try to write your own dockerfile

```
1. git clone https://github.com/ashithss/docker-nodejs.git
2. cd docker-nodejs
3. docker build -t nodejsApp:latest .
4. docker run --name node-app -it -p 3005:3005 -d nodejsApp:latest
5. Your application will run in 3005 Port:- http://localhost:3005/
```


The application is running on [localhost](http://localhost:3005).
