From SCOS platform
==

Reps:
1. Mackenzie King
1. Rob 
3. Ram - data curator 

Notes:
- SCOS 2.0 launched!
- UI does not look terribly different
- Are tracking data sets individually
- working on enhancing with categorization
- Next release date is JUNE
- Tomorrow night will be a deployment for quick search capabilities
  - robust capabilities for ingestion process
    - more near real time data
    - will be going opensource (JUNE 18 - announcement)
    - Smart city data platform will be available for other cities to use
    - Oct: Open source release
      - smart columbus open source
      - June 4th at Smart Columbus Experience
        - celebrate SCODE members


Data provider toolkits
- example in data.world

Volunteer to help provide data


Open Side Walks Project
==

West coast Reps

Reps: 
1. Nick Bolten - project leads (Webex)
2. Anat Caspi - project leads (Webex)

Notes:
- OpenStreetMap
- Need from an underlying pedastrian (access maps)

Are there sidewalks?
Are they too steep?
Will i run into obstructions?
Are there stairs? Can I avoid them?

Access maps
- Can prioritize pedestraian mobility data
- Change settings based on steepness/stairs/ramps
- Data cleaning, offset algorithms, crossing synthesis (months of dev)

what data should we track? what format?
- width of sidewalks
- curb data (lowered/raised/flush/rolled)
- surface info
- barrier info


What not to do with collecting data
- Do not collect a limitted set of data disconnected from the rest
- Disparrate objects that do not connect to each other cannot be used together (like for routing, etc).
- Where users went around and marked where there were obstacles (but it was not tied to the sidewalk network)

Create this network
- Where are sidewalks, where are crossings
- do NOT collect sidewalk data as meta data of the streets (they are not really connected)
  - have to go fix it if you want to use it later
- Want nicely connected pathways that describes different attributes of the pedastrian pathways

How do you start this?
- How do you get started with mapping the data?
  - What they currently do?
    - Open street map
      - host mapping parties, where they train people 
      - learn to use Armchair mapping tools
      - do a lot of tracing, but it is network tracing
        - Desktop application:
          - Power User
        - Many editors for open OpenStreetMap
          - Street complete (open source)
            - write a query for missing data
            - used in the past for crowdsourcing info about bus stops
              - find me a bus stop that does not have a trashcan/shelter/etc.
          - tasking manager
            - base url: tasks.openstreetmap.us
            
  - How can you add more detailed dta later?
  - What they want to do?


- Can we grab pictures from users

Community Service Locator Project Update - Mihir
==
1. Vijay
2. Mihir

findlocaltreatment.org
relink.org
- have data that is kept up to date
- have people in franklin county that are calling to confirm their data is up to date
  - they have a website that you can scrape pretty easily
  - it is updated every week
- working with OSU to build an application
- only requirement is to link to relink.org when displaying the data


Aging population data - Jesse
==
- kirwan project (see github project)
- Looking at the geo density for aging population
- Dense and vulnerabilities of senior populations
- OSU kirwan institute
- Do not just look at the data, look at the source (where it came from)
  - gets a better understanding of the data
- Sign up for the analytics site (jypter hub)

Insights
- Might be physical boundaries stopping people (ie: freeways)



Help needed
- analizing the data
- Jypter hub

github project
  - sources
    - where the data is provided in scose
  - data
    - csv's
    - geojson
  
tableau public
==
Chris
- tableau public
- density of people over 60 
- data is coming from?
  - ingested into tableau
  - census data from OSU
  - some other sources

- census track (should look at census block level - much more detail)


Purpleaisle - Andy Goldfarb
- community that will be open to manual mapping
- were in columbus Nov 2018
- Andy to reach out

Action Items
==
- Start a mapping party (focus on a specific area)
  - task.openstreetmap.us
    - start a project
- census block link - post by ?? - ayaz (OSU professor)
  - ipums
    - very detailed areas that gets at the underlying data that the census uses to give that data
- Test automation
- Accessibility
