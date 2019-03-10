## Rough agenda

1. 10-15 minutes from Mackenzie King on the state of things from the SCOS.
1. 10-15 minutes for existing project updates from leads. (https://github.com/orgs/SCODEMeetup/projects).
1. 70 minutes ( rest of meetup ) Ideation from [previous](https://talkcoffeeto.me/d/8tdQMBH93LBr9) voting
   * [Data Story](https://www.smartcolumbusos.com/data-stories/data-paves-the-way-to-help-older-adults-get-around)
1. Community Services Locator?
   * https://github.com/SCODEMeetup/community-services-locator-ui
   * https://github.com/SCODEMeetup/community-services-locator-api

## Data Story details

We should look over pages [76-90](https://github.com/SCODEMeetup/hackscos18-presentations/blob/master/Hackathon%20Presentation.pdf) from the Hackathon presentation.

1. [Geographic density of older residents](https://ckan.smartcolumbusos.com/dataset/dense-and-vulnerable-senior-populations)
1. Geographic distribution of vulnerable older residents - no clue
1. COTA transit schedules and routes
   * [COTA Calendar](https://ckan.smartcolumbusos.com/dataset/cota-calendar) - This dataset identifies the type of transit service active on different days of week between 05/07/2018 -09/02/2018
   * [COTA Trips](https://ckan.smartcolumbusos.com/dataset/cota-trips) - This dataset identifies the number of trips that happened per day on each of their Routes.
   * [COTA Lines](https://ckan.smartcolumbusos.com/dataset/cota-lines) - Data used for community planning in the City of Dublin, OH
   * [COTA Transit Route Shapes](https://ckan.smartcolumbusos.com/dataset/cota-transit-route-shapes) - This dataset represents the shape of COTA routes as a sequence of the latitude and longitude points
   * [COTA Transit Lines](https://ckan.smartcolumbusos.com/dataset/cota-transit-lines) - This dataset identifies the transit routes served by COTA. This data is reflective of transit services offered in 2018.
1. COTA one – minute refresh GPS data (archived and dynamic)
   * [COTA Real Time (raw)](https://ckan.smartcolumbusos.com/dataset/cota-real-time-feed) - COTA provides real time feeds for 1. Trip Updates and 2. Vehicle Position. Both the feeds are in GTFS format. This dataset updates every 15 seconds.
1. Sidewalk existance maps from MORPC
   * [Sidewalk Inventory](https://ckan.smartcolumbusos.com/dataset/sidewalk-inventory1)
1. Sidewalk condition data - could not find on scos
   * [MORPC sidewalk](https://1drv.ms/u/s!ArZcbDzlDSeQigK-n2ObKY-_G5Gx) data converted to shape. This was provided by Erick Lobao on the #scode slack channel
1. Crosswalk types and facilities - could not find on scos
1. Traffic/crossing signal cycles and timing - could not find on the scos
1. Locations of healthcare services, food services, shopping destinations and more
   * we would need to find / build or buy

## Possible additional sources of data / info / ideas

[Age Friendly Columbus](https://agefriendlycolumbus.org/)
   * [Report](http://agefriendlycolumbus.org/wp-content/uploads/2016/12/Age-Friendly-Columbus-Findings-Report.pdf) from 2017

## Seed ideas

1. Platform to crowd-source sidewalk impairment
   * Short pitch: An app people with their smart phone can tag obstacles.
      * Using the app, zoom to the sidewalk / street level where they are now
      * Allow the user to tap and add a new obstacle, selectable types
         1. uneven sidewalk
         1. some kind of obstruction, tree missing sidewalk etc? Kinda generic
      * The idea here is to develop a dataset which can be used for a few things
         1. dispatch queue for visual inspection
         1. Provide a browser based map for city planning
         1. Possibly create an output dataset for use by the multi-modal trip planning with special consideration for limited mobility? ( eg don't send a wheel chair where there are crazy sidewalk issues - route around it )
1. See if we can automate detailed map collection - eg crowd sourced but a different way
   * Short pitch: See if we can get accuracy from something like a drone with gps and image recognition
      1. Think of how cool it would be to get people with their drones to go race / map an area ;)
      1. This is for sure pie in the sky, I have no idea if its possible
   * Refinement ideas
      1. Reach out to drone [meetups](https://www.google.com/search?q=columbus+drone+meetup&oq=columbus+drone+meetup&aqs=chrome..69i57.2585j0j7&sourceid=chrome&ie=UTF-8) ( google search )
      1. Maybe something like [medium article](https://medium.com/nanonets/how-we-flew-a-drone-to-monitor-construction-projects-in-africa-using-deep-learning-b792f5c9c471) / [Nanonets](https://nanonets.com/drone/)
         * Note, nanonets has a fee structure. Not sure how we would cover costs there
      1. Maybe we could make our own service to run somewhere - [tensorflow](https://www.tensorflow.org/) anyone?
         * Google's [Coral](https://coral.withgoogle.com/)
            * USB or their dev board
         * Intel's [movidius](https://www.movidius.com/myriadx)
         * Raspberry pi or some offline processing, cheaper...
