# UFO Sightings with JavaScript

## Overview

Within the challenge we are doing to help Dana, data journalist. She is excited to prepare an article about her hometown McMinnville, Oregon, and,, even more excited about the topic UFOs. The purpose of the project is to prepare a table based on UFO observations. The table should have a feature of being filtered py different parameters simultaniously.
Within the project we relied on the following technologies:
* CSS, HTML and Bootstrap library
* JavaScript and D3.js library

The project rusults are deployed as a one-page website here: [UFO Sightings](https://arminekhanan.github.io/ufoSightings/?fbclid=IwAR08vbEpIGP0NE9V9m5K0yLr5ejo5JoZLddIxPYtIl-09kG7ZqpL60XocoQ).

## Results

### Filters

The user can interact with the table by applying the following filters, situated on the left-hand side of the webpage:

* Date, accepting Month-Day-Year without leading zeros format date values.
* City, accepting lowercase city name values.
* State, accepting lowercase USPS abbriviations of the states.
* Country, accepting ISO-3166-1 ALPHA-2 country code values typed lowercase.
* Shape, accepting lowercase one-word descriptions in english

All the filters have hinting text for entering values in the proper format.

<img src="https://github.com/ArmineKhanan/ufoSightings/blob/main/Screen%20Shot%202022-11-18%20at%205.15.40%20PM.png" width="500" />


### Apllying multiple filters and resetting
To run the filter the user should enter the value in an expected format and hit enter. Every filter accepts only one value at a time. Filters work in combination. To go back to the initial table content on can press the "UFO Sightings" text a the very top left-hand side of the page. 

<img src="https://github.com/ArmineKhanan/ufoSightings/blob/main/Screen%20Shot%202022-11-18%20at%204.56.49%20PM.png" width="500" />

## Summary

### Drawbacks of the webpage
One major drawback of the webpage is the data scarcity. It encompasses a limitted timeframe, from 1st to 13th of January, 2010, and the only Country represende is USA.

### Further development
The webpage can be improved in several regards.

#### Filters
* *Dropdown* menue might hint the customer to enter the value as stored in the database.
* In case of the wrong entry, that would be useful to have *handle different kind of typical errors* assisting the user to correct their mistake.
* The user experience might also be enhanced by enable them to opt for *more than one value* per filter

#### Table
* Sorting arow for every field is nessesary to look at the data in a more structured way
* For such projects it's crucial to give the user an opportunity to download the data
