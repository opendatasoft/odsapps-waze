ODS Apps Waze
=======

Waze App deployment consist into 2 main parts, the code itself but also the historic data collection process.


#####Pre-requisite:
 
You must be a Waze Connected Citizens Program (CCP) member to get access to Waze data on your territory.
OpenDataSoft can help you going through the process and setup your first realtime dataset on your ODS Portal. 

You also need to get in touch with your CSM to launch the data collection to start your historical dataset.

Then, it's a simple process of getting the assets and pages.
You'll need : 
 * to add the portal customization code to your portal (header and stylesheet)
 * to upload the assets (background images, logo and favicon)
 * to create the pages

Please find all the links and resources below.
 

## Get the code and assets

You can simply download the assets, portal header and stylesheet, and apply them to your portal.

**NB**: if your portal already have a customization, do not simply replace the stylesheet and header, you'll probably need to merge these files. Advanced HTML/CSS knowledge might be required. Ask your OpenDataSoft CSM contact for more information and help.

### Portal look and feel

* [Header menu (HTML)](./resources/web/header.html)
* [Portal stylesheet (CSS)](./resources/web/stylesheet.css)

### Pages

Real-time data view :

* [Waze App - Realtime (HTML)](./resources/web/realtime.html)
* [Waze App - Realtime (CSS)](./resources/web/realtime.css)

Historical data view :

* [Waze App - Historical (HTML)](./resources/web/historical.html)
* [Waze App - Historical (CSS)](./resources/web/historical.css)

Compare side-by-side your historical data :

* [Waze App - Compare (HTML)](./resources/web/compare.html)
* [Waze App - Compare (CSS)](./resources/web/compare.css)

Optionally, the default home page :

* [Waze App - home page (HTML)](./resources/web/home.html)
* [Waze App - home page (CSS)](./resources/web/home.css)


**N.B.:** The Waze App pages are all independent, you are not forced to get them all.


### Assets

* [Assets (zip)](./resources/assets/assets.zip)

The assets archive contains pictograms, logos, and background images. Do not hesitate to replace them with your own.
It may also require some CSS changes if the dimensions of your assets vary from these ones.

`favicon.ico` and `logo.png` should be uploaded in the `Look & Feel/Branding` menu of ODS Portal.
The rest in `Assets`.