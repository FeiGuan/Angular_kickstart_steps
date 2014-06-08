#Step0

##Quick Start

Install [Node.js](http://nodejs.org/)
Get [ng-boilerplate](http://joshdmiller.github.io/ng-boilerplate/#/home)
```shell
$ git clone git://github.com/joshdmiller/ng-boilerplate
$ cd ng-boilerplate
$ sudo npm -g install grunt-cli karma bower
$ npm install
$ bower install
$ grunt watch
```
<h3>ng-boilerplate</h3>
<b>ng-boilerplate</b> is the best Angular project template<br />
module layout: <br />
* src/				(all codes used in the application)<br />
      * app/			(app-specific codes)<br />
            * app.js		(main app configuration)<br />
            * app.spec.js	(app tests in jasmine)<br />
      * assets/			(static files: fonts, images, css)
      * common/		()
      * less/
      * index.html		(contains all markup applied to everything in the app, such as header and footer, declaring with ngApp="ngBoilerplate", controller and directive)
* testacular(or karma/)		(test configuration)
* vendor/			(third-party libs)
* Grunfile.js			(build script)
* package.json			(metadata)<br />

<h3>Grunt</h3>
ng-boilerplate uses [Grunt](http://gruntjs.com/) as its build system, which automates gathering assets for distribution compiling LESS into CSS, linking and minifying JS sources and running unit tests. [Gruntfile.js](https://github.com/ngbp/ngbp/blob/v0.3.2-release/Gruntfile.js) is config file.
<br />
<h3>Karma</h3>
Running unit tests


