### Fusion Seed App
This application will help you get up and running with Fusion.

## Install & Run

### Requirements
You need to have `node` & `npm` installed.

#### Before you start
Make sure you have the right build tools installed
```
npm install -g bower gulp
```

#### Starting the app
```
git clone https://github.com/LucidWorks/lucidworks-seed-app
cd lucidworks-seed-app/
cd ui/
npm install; bower install
npm start # This will serve files on http://localhost:8079
```

### To build for deployment
```
cd lucidworks-seed-app/ui/
npm build
```
The `ui/build` directory will have all the static files that can be served from a regular file-server.

### Configuration
In order to configure the application you can use the settings in the `config.js`.