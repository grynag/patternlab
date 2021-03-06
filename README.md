# Creating technology-agnostic styleguides with Pattern Lab

This workshop will give a short introduction to how we can build re-usable and easily maintainable front-end components using Pattern Lab.

We'll start with a presentation of styleguides and Pattern Lab, then have a coding session and finish with exercises
if we have time. 

## What you need
* Node 4.X+ (https://nodejs.org/en/)
* Global installation of Gulp CLI (`npm install gulp-cli -g`)
* Your favourite editor ([VS Code is a nice alternative](https://code.visualstudio.com/))
* A command-line application (if not available inside editor)

## Getting started

We will start with creating your own fork of this repository. Make sure you're logged in and click the Fork button up right. Clone the repository to your local computer by opening command line, navigate to the folder you wish to work from, and type git clone `<Your new repo url>`

Navigate to the repository folder, inside the `patternlab` directory run the following commands:

If you haven't installed the command line interface (CLI) for Gulp yet, do so by installing it globally. From the command line type:

`npm install gulpjs/gulp-cli -g`

Once we have installed Gulp CLI globally its time to install the application dependencies using NPM. In your command line, navigate to the styleguide directory within our repo and type the following:

`npm install`

Once all dependencies are installed, we should be able to generate our Patter Lab solution. From the command line, still standing within the styleguide directory, type the following command (heads up, this command will open up your default browser):

`gulp serve`

This executes one of the main gulp tasks which compiles our solution. The task starts up a local web server that hosts the solution and the task will keep running and listen for changes on certain files within our solution.

The application will now open in your default browser at url: http://localhost:3000.

## Exercises
You can choose between two exercises. 
1. Refactoring of the `news` template: [Exercise 1](exercise1/) 
2. Create your own home page template with new components: [Exercise 2](exercise2/)

## Reference materials
* [Pattern Lab documentation](http://patternlab.io/docs/index.html)
* [Mustache documentation](https://mustache.github.io/mustache.5.html
)
* [Blaze UI documentation](https://www.blazeui.com)