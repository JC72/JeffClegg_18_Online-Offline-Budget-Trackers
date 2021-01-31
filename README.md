# JeffClegg_18_Online-Offline-Budget-Trackers

This project was designed as a homework assignment for MSU's coding bootcamp. 

This project has been loaded to my Personal GitHub Page and deployed to my Heroku account. To get this project up and running, you can follow the deployment link that I have included in the Link Section below.

# Table of Contents
1. [Links](#Links)
2. [Project Overview](#projectoverview)
3. [Demo](#demo)
4. [Assignment](#assignment)
5. [File Structure](#filestructure)
6. [License](#license)
7. [Execution](Execution)
8. [Credit](#credit)
9. [Creators](#creators)

## Links

* [GitHub Repository](https://github.com/JC72/JeffClegg_18_Online-Offline-Budget-Trackers)
* [Active Site](https://cryptic-mountain-17754.herokuapp.com/)

## Project Overview <a name="projectoverview"></a>
* Uses CSS, Node.js, JQuery, JSON, Express, mongoose, MongoDB, compression, lite-server and Heroku to create a progressive web app (PWA) which allows the user to add new transactions and deposits to the chart whether the user is online or offline.  It stores the offline data till the app is back online and updates the database.

## Demo:

![](https://github.com/JC72/JeffClegg_18_Online-Offline-Budget-Trackers/blob/main/public/assets/video/demovideo.gif)

## Assignment
### This assignment contains the following features:

* Main Page
    * Contains a header that totals the amount of money you have.
    
    * Two input fields that allows you to enter the name of the transaction and the amount

    * A add button to let the user make a deposit amount.

    * A subtract button to let the user withdraw or make a payment amount in the tracker.

    * A graph that tracks all transactions by date and amount.

    ![Home Page](https://github.com/JC72/JeffClegg_18_Online-Offline-Budget-Trackers/blob/main/public/assets/screenshots/homepage.png)

    ![Home Page](https://github.com/JC72/JeffClegg_18_Online-Offline-Budget-Trackers/blob/main/public/assets/screenshots/apponline.png)

    ![Home Page](https://github.com/JC72/JeffClegg_18_Online-Offline-Budget-Trackers/blob/main/public/assets/screenshots/appoffline.png)



## File Structure <a name="filestructure"></a>

The following folders and what they contain are listed below:

```bash
  |-- JEFFCLEGG_18_Online-Offline-Budget-Trackers
    |-- models
    |   |-- transaction.js
    |-- public
    |   |-- assets
    |   |   |--screenshots
    |   |   |   |-- homepage.png
    |   |   |   |-- appoffline.png
    |   |   |   |-- apponline.png
    |   |   |--video
    |   |   |   |-- demovideo.gif
    |   |-- icons
    |   |   |--icon-192x192.png
    |   |   |--icon-512x512.png
    |   |-- db.js
    |   |-- index.html
    |   |-- index.js
    |   |-- manifest.webmanifest
    |   |-- service-worker.js
    |   |-- style.css
    |-- routes
    |   |-- api.js
    |-- .gitignore
    |-- LICENSE
    |-- README.md
    |-- package-lock.json
    |-- package.json
    |-- server.js
```

## License

This project is licensed under the MIT License License

![Badge for GitHub repo license](https://img.shields.io/github/license/JC72/JeffClegg_18_Online-Offline-Budget-Trackers?style=flat&logo=appveyor)

## Execution
### To Execute File:
> Just click on the Active site link in the link section or go to
https://cryptic-mountain-17754.herokuapp.com/ in the web browser.


## Credit

* Would like to thank stackoverflow for helping me find fixes for some of my conflicts.  Especially with my problem when I was trying to fix the deployment issue with Heroku.

* [Stack Overflow](https://stackoverflow.com/)

## Creators:

* **Jeff Clegg** - [Git Hub Profile](https://github.com/JC72)
* MSU BootCamp