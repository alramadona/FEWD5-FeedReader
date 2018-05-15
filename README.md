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

## Tests
* RSS Feeds
    * each has a URL defined
        * the URL is not empty
    * each has a name defined
        * the name is not empty
* The menu
    * is hidden by default
    * visibility changes when the menu icon is clicked
* Initial Entries
    * be loaded with at least one entry element within the feed container
* New Feed Selection
    * the content changes when a new feed is loaded

## Credits
The repository for the starter code can be found on [Github](http://github.com/udacity/frontend-nanodegree-feedreader).