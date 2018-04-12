## Gulp Starter Pack
This package intended to solve common front-end development tasks. Works best for psd/sketch to html projects and save you a lot of time setting up local environment

## How to start
* `yarn` - install npm dependencies
* `bower install` - install bower packages
* `gulp` - run dev-server
* `gulp build` - build project from sources

## List of Gulp tasks
To run separate task type in command line `gulp [task_name]`.
Almost all tasks also have watch mode - `gulp [task_name]:watch`, but you don't need to use it directly.

### Main tasks
Task name          | Description                                                      
:------------------|:----------------------------------
`default`          | will start all tasks required by project in dev mode: initial build, watch files, run server with livereload
`build:development`| build dev version of project (without code optimizations)
`build`            | build production-ready project (with code optimizations)
