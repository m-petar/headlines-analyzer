# headlines-analyzer

This app allows you to browse through a collection of news headlines and see which words appear most frequently in them.

Each word will be visually represented by the first image returned by Google image search.

User-specific analysing tool will also offer headline suggestions based on previous headline links visits.

Time-range can also be set and if left blank, the whole collection will be evaluated.

The app was built in PHP and uses Twig template engine to render html pages.
News headlines collection is updated daily using cron job scheduler that runs a php script to crawl three chosen news websites
and stores data in a PostgreSQL database.

Link to the app on Heroku: https://headlines-analyzer.herokuapp.com/ <br>
Please use these credentials to test it: <br>
Email address: ```test@mail.com``` <br>
Password: ```novasifra28```
