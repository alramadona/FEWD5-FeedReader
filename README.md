# Feed Reader Testing
## Project Overview
This project contains a web-based RSS feeds reader application utilizes [Jasmine](http://jasmine.github.io/) testing suite. Open the **index.html** file to open the application and execute the tests.

## Files
* `.\css\`
    * icomoon.css
    * normalize.css
    * style.css
* `.\fonts\`
    * icomoon.eot
    * icomoon.svg
    * icomoon.ttf
    * icomoon.woff
* `.\jasmine\`
    * `..\lib\`
        * `...\jasmine-2.1.2\`
            * boot.js
            * console.js
            * jasmine_favicon.png
            * jasmine-html.js
            * jasmine.css
            * jasmine.js
    * `..\spec\`
        * **feedreader.js** this is where the test suites are written
* `.\js\`
    * app.js
* `index.html`

## Suites and Specs
* RSS Feeds
    * are defined
    * all has defined URL
    * all has defined name
* The menu
    * is hidden by default
    * visibility changes when clicked
* Initial Entries
    * loaded with at least one entry
* New Feed Selection
    * do not match previous loaded feed

## Credits
The repository for the starter code can be found on [Github](http://github.com/udacity/frontend-nanodegree-feedreader).