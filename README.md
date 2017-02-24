# Golden Memory Local Dev Environment

Actually, we don't need the local dev env for both frontend and backend.

Wechat frontend has a WYSIWYG IDE and the code will be hosted in wechat itself, not our sever.

Our backend use java*&gradle, it takes care all the things including build the docker image, please refer to backend repo for details.

This local dev will only initialize all other dependencies like database or file server.

## Prerequisite
* [docker](https://docs.docker.com/engine/installation/mac/#/docker-toolbox)
* [docker-compose](https://docs.docker.com/compose/install/)

## Instructions
1. **Code-base preparation**

  Save the needed codebases on the same dir as this one, make the dir tree look like the following.

  So the dir tree will look like this.
  ```
  .
  ├── api
  ├── localdev
  ├── XXX
  ├── XXX
  └── XXX
  ```

2. **Startup your new local environment**

  ```
  ./auto/up
  ```
  After the initialization process is successful done, you can see your local environment in your browser.
