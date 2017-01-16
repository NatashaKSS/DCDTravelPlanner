# DCDTravelPlanner
A simple trip planner made on Azure web services using HTML, CSS, JavaScript and Bing Maps API

# Setting up your own Azure Web app

## Prerequisites:
* Have an azure pass or a free azure subscription to host a web app.
* Have an appropriate app service plan and azure resource group set up.

## Ensuring you have the correct app information
1. Upon creating your web app, you will be brought to a page that will display the essential pieces of information about your web app.
2. Click on "deployment credentials" and input a custom username and password for your FTP deployment server.
3. In the overview page, take note of the FTP/deployment username and FTP hostname. (Since we do not require an FTPS service, ignore the FTPS hostname field)

## Getting started with hosting your web app
### Prerequisites
* Have your favourite FTP client downloaded (recommended: FileZilla)   

#### Here, we will host our website by using an FTP client to communicate with your newly created online azure web service. It's really simple.   
1. You will need an FTP client which will connect to your azure web service and allow you to transfer your website project's files to and from that hosted web server.
2. Assuming that you're using FileZilla,
  1. Set "host" in FileZilla as your web app's FTP hostname without the "ftp://" prefix in the URL.
  2. Set "Username" in FileZilla as your web app's FTP/deployment username (together with the "/" and name after that slash).
  3. Input your FTP deployment "Password" in FileZilla.
  4. Click on Quickconnect.
  You should be directed to your web app's server directory.
3. Copy your website's project files into the folder "wwwroot"
4. View your website being hosted on your web app's URL.
5. Enjoy your app!
