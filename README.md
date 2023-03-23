# wildrydes

A rebuild of the serverless website WildRydes Workshop in Vue.js with AWS Amplify CLI.

Lesson website:
- https://webapp.serverlessworkshops.io/
- Original src: https://github.com/aws-samples/aws-serverless-webapp-workshop/tree/main/resources/code

## Prerequisite

- Nodejs version v16.16.0, otherwise see error below in TROUBLESHOOTING

## Project setup

- Commented out two lines in `main.js`, since we are not using Amplify
```
//import awsconfig from './aws-exports'

//Amplify.configure(awsconfig)
```

- Install
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

## RUN
```
$ npm run serve


> wildrydes@0.1.0 serve
> vue-cli-service serve

 INFO  Starting development server...
98% after emitting CopyPlugin

 DONE  Compiled successfully in 48507ms                                                                                                          3:17:05 PM

  App running at:
  - Local:   http://localhost:8080/ 
  - Network: http://172.19.183.38:8080/

  Note that the development build is not optimized.
  To create a production build, run npm run build.

```


