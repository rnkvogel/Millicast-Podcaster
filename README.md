# Millicast-Podcaster
Millicast Audio Only Podcaster

This is a customizable audio only podcaster that can be used on your web site for 1 to many real time audid only streams.
Live streams to all devices.

You will need a Millicast account to get started.
https://millicast.com/

Once you have created a Millicast account you will need to create a live stream token.
1. In your Millicast portal(+) Add a new token M
Make sure to select Use ANY name for this set up!!!!!!
Security options can be set up with this example using the Millicast API.


Download the files.
Open these files with a text editor.
1. Open the JS/Publisher.js file.
2. Open the JS/viewer.js file.
EDIT THE FOLLOWING

let accountId = ''YOURID'; //let accountId ADD YOUR ACCOUNT ID HERE

let token ="REPLACE WITH YOUR TOKEN";   //YOUR TOKEN FOR STREAM goes HERE

EDIT THE FOLLOWING ON PUBLISHER JS.
1. Open the JS/Publisher.js file.
let token ="YOUR TOKEN GOES HERE";

Place the folder on your website 

https://YOUR_WEB_SITE/podcaster/?id=ANY_NAME

Customize the publisher and player as you want.


