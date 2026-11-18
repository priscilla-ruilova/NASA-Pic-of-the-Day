# Project: 🚀 Project: Simple NASA API

A simple web app making use of the NASA picture-of-the-day web API(POD). This app enables the user to enter a date and returns the picture/video of the day from [NASA's API](https://api.nasa.gov/assets/files/apod/APOD-APIs-and-RSS-info.pdf).

## Live Link
You can check out this simple web abb by [clicking here!](https://priscilla-ruilova.github.io/NASA-Pic-of-the-Day/)

![screenshot of web page](assets/photos/screenshot.png)

## Tech Stack
- HTML, CSS, JavaScrip, Web API: NASA Picture of the Day API

## Issues that came up:
- Because some pictures are actually videos instead, I needed to create conditionals that ran depending on what the media type was. 
- While styling, I ran out of tokens so it's good to think about alternative options for protecting token usage. A colleauge suggested creating a local JSON file to fetch the data. 