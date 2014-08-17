[![LCDM Logo](http://lcdm.astro.illinois.edu/theme/images/LCDM-logo.png)](http://lcdm.astro.illinois.edu/xprojects/cswebapp.html)

The Laboratory for Cosmological Data Mining was founded in 2002 at the University of Illinois by Professor Robert J. Brunner to develop and apply computational technologies to extract cosmological information from the large astrophysical data sets being generated within our community. LCDM has been one of the top twenty users, worldwide of the production supercomputing resources at NCSA.

This project is completed as a part of Google Summer of Code 2014. The goal of the project is to create a Platform where arbitrary Crowdsource project can be set up and can be used to generate gold standard data for various application through crowdsourcing.

The main aim for the project was to enable more general crowdsourcing experiments where there is a Interactive GUI for both data presentation and classification gathering. 
As a result, in this project, we developed an entirely new user interface to enable a human user to easily view, identify, and tag features within an experiment setup through this platform. 

The Admin can be able to setup any croudsource experiment based on images, videos etc.
In Addition, user will be able to select pre-assigned labels, as well as enter free-form text to describe unusual or interesting classes in the corresponding experiment.


## Technologies Used

1. [MongoDB](http://www.mongodb.org/), 
2. [Node.js](http://www.nodejs.org/), 
3. [Express](http://expressjs.com/), and 
4. [AngularJS](http://angularjs.org/).

We have used the MEAN.JS is a full-stack JavaScript open-source solution, which provides a solid starting point for developing the platform.


## Prerequisites to Setup the platform
1. Install Node.js - [Download & Install Node.js](http://www.nodejs.org/download/) and the npm package manager.
2. Install MongoDB - [Download & Install MongoDB](http://www.mongodb.org/downloads). It should run on the default port 27017.
3. Install Bower - [Bower Package Manager](http://bower.io/) to manage front-end packages. Install it globally.

```
$ npm install -g bower
```

4. Install Grunt - [Grunt Task Runner](http://gruntjs.com/) to automate development process.

```
$ sudo npm install -g grunt-cli
```


To install Node.js dependencies you're going to use npm again, in the application folder run this in the command-line:

```
$ npm install
```

This command does a few things:
* First it will install the dependencies needed for the application to run.
* If you're running in a development environment, it will then also install development dependencies needed for testing and running your application.
* Finally, when the install process is over, npm will initiate a bower installcommand to install all the front-end modules needed for the application

## Running the Web Application
After installing all the prerequisites Go to root folder of the source tree and run
1. `grunt test` to run the test suite.
2. `grunt server` to run the webapp.
 
The application will run on the 3000 port in the browser. Go to [http://localhost:3000](http://localhost:3000)

## License
(The MIT License)

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.