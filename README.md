# Single-Page-App-CMS
The structure of content.json is an array of objects. Each element in this array is an object with three keys: title, abstract, long. Every key and every value is of type string.
Populate this JSON file with content for different titles, e.g. home, ucc, personal.
Clear layout. The main elements are now navigation, theme switching, content window, view toggle and status message line. 
When the page is initially loaded, a JS function will be activated which fetches content.json and saves the contained array as a global variable.
For each title, an identically labelled navigation button is automatically created in the navigation bar.
Clicking on a title button in the navigation bar display the corresponding content in the main area.
At an appropriate location there is a button for toggling between abstract and long content view. 
The default view after the page has loaded content element 0 is shown and abstract view is enabled.
Modifications in content.json automatically take effect as soon as the unmodified file cms3.html is reloaded. 
fetch function load the JSON array into a global variable.
