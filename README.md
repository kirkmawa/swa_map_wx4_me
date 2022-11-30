# Weather4Me Interactive Alert Map

This is the source code for the web application running at https://map.wx4.me. 

## What this web app does

This web application displays a map overlaid with a NEXRAD weather radar mosaic and severe weather warning polygons from the US [National Weather Service](https://weather.gov). Clicking on any polygon will serve a map element containing more information about the alert. Users are also able to locate their device by clicking a button to automatically zoom to their local area. It is meant to be a graphical representation of some information provided by a companion web app at https://wx4.me ([GitHub repo here](https://github.com/kirkmawa/swa_wx4_me)).

## Contributing
You are welcome to fork this repository and open pull requests to improve the application. This web app is hosted on the Azure Static Web App service, so all operations must be client-side.

## Respect the Polygon
"Respect the Polygon" is a phrase popularized by legendary Alabama television meteorologist James Spann. It is meant to remind his audience that forecasters at the National Weather Service are experts in their field, and if a given location is inside one of these storm-based warning polygons, there is a very good reason for it. Anyone inside the warning polygon should take action to protect themselves from natural hazards. This app is my effort to help people quickly determine whether they should take these actions.