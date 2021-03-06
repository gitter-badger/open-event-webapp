# open-event-webapp
Open Event Webapp

The Open Event Webapp

The webapp is a generic app that has two parts: a) A standard configuration file, that sets the details of the app (e.g. color scheme, logo of event, link to JSON app data) b) The webapp itself

##Features
This is a client-side webapp, that will be used by attendees of the event. For Android users we have a native android [app](https://github.com/fossasia/open-event-android). This webapp provides similar functionality for platforms other than Android, that is, to be able to view details about - 
 1. Speakers
 2. Sessions
 3. Tracks
 4. Map
from the event, with latest available data. 
It will be responsive, so that it can be viewed from all screen sizes easily. 
The data will be fetched dynamically from the API endpoint provided by the ![orga-server](https://github.com/fossasia/open-event-orga-server). 

##Deployment
Currently it is just a simple webapp that can be viewed using any browser. In future, we plan to deploy as a webapp for Ubuntu Phone, Firefox OS etc, who support first class webapps. Also for platforms like iOS, Windows, we might port this usin Ionic/Titanium etc. 

##Technology
 * AngularJS 2.0
 * Bootstrap (or similar) for styling
The webapp will be written using only HTML, CSS and Javascript, so it is completely client-side renderable, on all kinds of browsers, including PCs and smartphones and tablets. 
