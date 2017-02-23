# Golden Memory Local Dev Environment

This is the guide of golden memory local developmemt environment build.

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
