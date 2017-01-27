The angularjs.org site is not designed to be used by third parties.
It is only kept here as part of our own deployment processes.

If you want to have a go at hosting it yourself you can try running

    yarn run build

This will build the website in the `build` folder, which you can then serve with something like:

   cd build
   http-server

and browse to http://localhost:8080

**Note: we do not be provide support for doing this.**

The site relies upon accessing numerous additional resources from all over the web.

Hint: to access the AngularJS docs application rather than this site, which is only the homepage,
 clone the main project and build the docs yourself...

    git clone https://github.com/angular/angular.js.git
    cd angular.js
    npm install
    grunt package webserver

Then browse to http://localhost:8000/build/docs/api
