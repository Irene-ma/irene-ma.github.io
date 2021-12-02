---
layout: project
type: project
image: images/coastarbg.png
title: Coastar
permalink: projects/coastar
date: 2021-11-30
labels:
  - Javascript
  - MongoDB
summary: Meteor Web Application to report marine sealife sightings and injuries in Hawaii
---

## Links 

Github Page for our project is located [here](https://github.com/HACC2021/Big-Brain-Coders) <br />
Our deployed application is located [here](https://coastar491.meteorapp.com/#/)

## Description
<img class="ui medium right floated rounded image" src="/images/reportseal.png">
For the Hawaii Annual Coding Challenge hackathon, our team decided to take on Hawaii Marine Animal Response's (HMAR) challenge in creating an application where people can report marine animal sightings such as monk seals, seabirds, and turtles. As of now HMAR only has their phone number listed on their site for people to report sightings or an injuried animal. This can pose problems because sometimes it's hard for people to hear over the phone from background noise and sometimes people won't know their exact location. We went and developed an application that has a report feature for people to input various information such as what type of animal they spot, a description, a picture of the animal, and also pulls up Google map for people to mark their location.   
<img class="ui medium left floated rounded image" src="/images/listreports.png">
Our application also has admin and member accounts for members of HMAR to log in and view a listing of reports from people and also a map where all the reports have been marked. This makes it easy for the members to plan out which area to go to and also to track how many reports have been made in a particular area. On the map, members can also click on each marker on the map and it will show a little information window associated with that marker. The information window shows a picture of the reported animal along with what type of animal it is. This will help members quickly check multiple markers and see which animal has been reported. 

## What I Gained
This years HACC was definitely the hardest year I have encountered compared to the previous HACC's i've participated it. Because of course load, my team and I struggled to put in the amount of work we wanted to into this hackathon. Even though we made the effort to meet up together and tackle on the project, our school work took the best of us. We also dealt with a lot of problems and made things harder for us. One thing was trying to integrate Google map's API into our meteor project. We were under the assumption that we had to pay to use their API so we were trying to make a workaround with the API by using pure Javascript. This proved a lot of work because we ran into issues and things not working. But after the hackathon when we all had more time to work on the project, I found out that we were able to use the API for free which made developing the map so much more easier. From then, we were able to do a lot of features done and I was able to figure out my problem.
<img class="ui medium right floated rounded image" src="/images/marker.png"> I gained a lot of valuable lessons during this HACC. I experienced how constricted time and school load affected our ability to put in our best effort and also learned so much about using Google map's API. I had some trouble with incorporating the API to work with meteor but my team members were able to help me out and teach me what to do. This really helped me a lot in understanding Google's API. 

## Personal Contribution
<img class="ui medium left floated rounded image" src="/images/markerinfo.png">
On this project, I focused on improving the functions for the Google map. Me and a team member worked on getting each marker to show up on the map that was associate with each report. I was in charge of developing an information window for each marker to show additional information that was associated to that marker. Initially I was running into a lot of trouble because I wasn't using Google's API. I was trying to do a pure JS solution but it wasn't working. I tried out multiple solutions and reached out to my team members to see if they could help me. It wasn't until switching to using Google's API that I was able to get my initial solution working. After hours of researching and reading the documentation on Google map's API, I feel like I would definitely use this API on later projects. It was such a useful tool and easy to use once I figured out how to integrate it with our project. 
