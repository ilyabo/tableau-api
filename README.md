Note: This project is using a older version of the Tableau Embedding API (v2.0.0, whereas v3.4.X is currently available)

To use a more up-to-date api version you can either:
* Manually download, copy, and export a version of the tableau API (as this repo's "tableau-api" dependency does). Eg from `https://public.tableau.com/javascripts/api/tableau.embedding.3.latest.js` as per the [Tableau docs](https://help.tableau.com/current/api/embedding_api/en-us/docs/embedding_api_get.html).
* Use an up-to-date project (such as the [TableauEmbed](https://github.com/stoddabr/react-tableau-embed-live) react component)

# Tableau API

This is a version of the 
[JavaScript API for Tableau](http://www.tableau.com/new-features/javascript-api) 
wrapped as an NPM module.

## Usage 

Add the following dependency to your package.json: 

    "dependencies": {
       "tableau-api": "git://github.com/ilyabo/tableau-api"
    }


Then, require it in your code:

    var tableau = require('tableau-api');
    
    
Refer to [the API documentation](http://onlinehelp.tableau.com/current/api/js_api/en-us/help.htm)
for the details on how to use it.
