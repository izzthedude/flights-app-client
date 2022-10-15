
This repository contains the a simple web application front-end application, built with React.js, called `Flights`. The `Flights` front-end communicates with a back-end API project (which should already be up and running when this app is started).

## Build and run the app

To start and run this application you need to execute the following commands within the root folder of this repo.

1. Install the Node.js packages (dependencies) for the app.

```bash
npm install

npx browserslist@latest --update-db
```

2. Run the the app, which will available via http://localhost:3000.

```bash 
npm start
``` 

If you encounter this error: `Error: error:0308010C:digital envelope routines::unsupported`, try running the app using this command instead:
```bash
NODE_OPTIONS=--openssl-legacy-provider npm start
```

## API Projects

This repo is configured as a [git submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules) within the following repos:

* [flights-app-nodejs](http://github.com/mariadb-developers/flights-app-nodejs)
* [flights-app-python](http://github.com/mariadb-developers/flights-app-python)
