# Knight Lab reveal.js template

## Installation

The **basic setup** is for authoring presentations only. The **full setup** gives you access to all reveal.js features and plugins such as speaker notes as well as the development tasks needed to make changes to the source.

### Basic setup

The core of reveal.js is very easy to install. You'll simply need to download a copy of this repository and open the index.html file directly in your browser.

1. Fork this repo.
2. Clone the forked repo to your local machine and use this new repo for your own presentation.
3. Open index.html in a browser to view it (note: run a local server for the custom Knight Lab typography to work).
4. Edit the slides in index.html with your own content.


### Full setup

Some reveal.js features, like external markdown, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/)

2. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

4. Clone the reveal.js repository
```sh
$ git clone https://github.com/hakimel/reveal.js.git
```

5. Navigate to the reveal.js folder
```sh
$ cd reveal.js
```

6. Install dependencies
```sh
$ npm install
```

7. Serve the presentation and monitor source files for changes
```sh
$ grunt serve
```

8. Open <http://localhost:8000> to view your presentation

You can change the port by using `grunt serve --port 8001`.

### Theming

If you want to edit the Knight Lab theme or create a new theme, read the [theming documentation](https://github.com/hakimel/reveal.js/blob/master/css/theme/README.md). The Knight Lab theme is controlled in `knightlab.scss`.


### Folder Structure
- **css/** Core styles without which the project does not function
- **js/** Like above but for JavaScript
- **plugin/** Components that have been developed as extensions to reveal.js
- **lib/** All other third party assets (JavaScript, CSS, fonts)
