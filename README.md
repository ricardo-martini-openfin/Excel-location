# Excel-location

An example code base using the OpenFin App to set a specific download location for an Excel file and a PNG. If you click the download it should automatically open.

## What you get:
A simple Openfin app that allows you to set an default download location
An example of an HTML, CSS, and app.JSON where you can set a download location
File opens upon clicking the download

## Getting started:
Testing `setFileDownloadLocation` (application manifest)

Make sure you have a DOS file with `setFileDownloadLocation` set to true

To test `setFileDownloadLocation`, launch the repository (npm install && npm start).
Set the `downloadLocation` const in the index.html to the desired path.
Click on the hyperlinks to test if the file gets downloaded to the desired path.
As soon as you click it should open the file.

## Expected behaviour:

Application should download both an example PNG and XSLS to your desired location based on the link you click.

Before clicking on the hrefs, right click in application and open devtools (inspect).

You should be able to see console messages that show the path is set.

Once you click on the hyperlink it should show the file being loaded and it should open.
