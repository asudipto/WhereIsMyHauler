# WhereIsMyHauler
This is a Web App that tracks your hauler fleet on a Tomtom Map.
It can provide tracking service to fleet operators, for objects of various types.


# How to use this?
This can be used in two ways:
| a) Locally - described in section below. Can be deployed on a Mac or a PC
| b) Via Internet - please take help from your technical team to follow this path. Do consider adding good security measures for the deployment

To use this locally (from a Mac/PC at your office/home),
i)     Install nodejs and related http-server package
ii)    Download the source code from this repository as a zip and extract it
iii)   Use command line program and navigate to the extracted folder that contains index.html
iv)    Run http-server at the command line
v)     Open a browser
vi)    Navigate to http://localhost:8080/index.html
vii)   Fill in the fields for Tomtom API key, Admin key and Project Id and click on Track Objects


Its assumed that you've already created Fences and Objects referring to Tomtom's Developer portal:
https://developer.tomtom.com
and the following - 

Create Fences with Tomtom Developer portal's the Fence Creator:
https://developer.tomtom.com/geofencing-api/tutorials/fence-creation


Create Object documentation is here:
https://developer.tomtom.com/geofencing-api/geofencing-api-documentation-objects-service/add-new-object

Postman collections for various APIs are here:
https://github.com/josejoserojas/TrackingFamilyPostmanCollection - including Create Object
(and here:
https://github.com/tomtom-international/postman-collections)

