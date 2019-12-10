# IBMWatson-imageanalyzer-NodeRed
A get you started in NodeRED with the power of IBM Watson for image analysis. 

This flow make use af a HTTP server for uploading the image to IBM Watson and displaying it's findings to the user. Everything is free to use and you will be able to set it up in minutes.

## The flow
![Alt text](/Node-RED-Flow.png?raw=true "Screenshot of Node-RED-Flow")

## How to setup:
1. Copy the flow into your clipboard from "Node-RED-Flow.yml" in this repo
2. Go to you Node-RED instance
3. Click on the hamburger icon in the top right corner
4. Go to Import > Clipboard
5. Paste the content in the gray box and "New Flow" should be selected
6. New flow is succesfully added

* In this setup we assume you already have a Node-Red instance running in the IBM-Cloud. Both are free to run! Additional advantage is that you don't have to mess with the IBM-Watson API keys or install its nodes. It isn't hard but we try to be lazy here.

You can create a IBM-Cloud account here: https://cloud.ibm.com/login <br>
You can see how to start with Node-RED on IBM here: https://nodered.org/docs/getting-started/ibmcloud

## How to use
1. Go to the same URL as your Node-RED instance with "/upload" behind it
2. Upload a image
3. See the result

## Screenshot of a result
![Alt text](/Example-lion.png?raw=true "Screenshot of a result")
