# Homelab_webapp

A little vue project

# Npm
[npm](https://github.com/npm/cli) is required for running the project. Personally I use [nvm](https://github.com/nvm-sh/nvm). With nvm you can run multiple node version and npm versions.

## Getting started
### Install correct node version
There is a file .nvmrc which contains the node version required to run everything. To install that version using nvm just run the following command:
```
nvm install
 ```
This will install the node version specified in the .nvmrc file.

### Install dependencies
Run the following command to install all the required dependencies
```
npm install
```

### Running the application for development
This will start the server in development mode
```
npm run dev
```

### Compile and Minify for Production
```
npm run build
```

### Initial project setup
These are the initial commands to do the initial project setup, and do not need to run again.
```
mkdir homelab_webapp
cd homelab_webapp
npm init vue@latest
mv homelab_webapp/* .
npm run dev
```

