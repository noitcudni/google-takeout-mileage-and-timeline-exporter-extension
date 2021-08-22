# Overview
Assuming that you've already been letting Google tracking your movements via your smart phone, you can have assess to all your location data for free. This extension helps you siphoning through that massive amount of data and distills them to useful bits of information for you to download in CSV format. This is a great tool for generating reports for your business needs.

Other existing products rely on Google's Timeline API behind the scene. Due to Google's rate limiting on the API, it may be difficult to get data across even just several months. My chrome extension, on the other hand, processes Google's Takeout data, so that it can easily crunch through multiple months worth or even years worth of data in one go.

By the way, it also handles timezone.

# Instructions
## Download your location data from Takeout
![Google Takeout](/images/takeout.png)
* Visit https://takeout.google.com/
* Make sure you check Location History. Probably should uncheck all the others to keep the file size manageable.
* Click on `Next Step`.
* Leave the default option as is, ie. frequency should be on `export once`.
* Click on `Create export`. Don't unzip the zip file.

## Extension Usage
* Click on the red marker near your Chrome's address bar.
* Enter your email and license. You'll only need to do this once.
* You'll be greeted with the following
![extension](/images/extension_panel.png)
* Fill in the `Start Date`, `End Date` and select a timezone.
* Click on `Submit Your Google Takeout Zip File`

## Timeline Tab & Mileage Tab
The timeline tab pretty much gives you the raw data unadulterated, so if you need more control when it comes to slicing and dicing your data, this view is for you.

The milesage tab lets you filter based on modes of transporation, start, and end locations.
