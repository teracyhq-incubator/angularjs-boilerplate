angularjs-boilerplate
=====================

The starting point to start any new AngularJS applications.


This project is generated with [yo angular generator](https://github.com/yeoman/generator-angular)
version 0.11.1.


Build & Develop
---------------
- Setup:

  + Get iorad-dev running by following: http://dev.teracy.org/docs/getting_started.html
  + Clone this repo to `~/workspace/personal/angularjs-boilerplate`
  + Then:

   ```
   $ vagrant ssh
   $ ws
   $ cd personal/angularjs-boilerplate
   $ npm install
   $ bower install
   $ bower update
   ```

- Run `grunt` for building and `grunt serve` for preview.


- Use `$ yo angular:*` to generate routers, controllers, directives, services, etc.

Test
----

`sudo apt-get install libfontconfig -y` first, then:

Executing `grunt test` will run the unit tests with karma.
