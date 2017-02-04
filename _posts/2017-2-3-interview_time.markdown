---
layout: post
title:  "Angular-2 Group Project"
date:   2017-2-3 20:18:04
categories: objects
intro: Well my last week with Angular-2 has been good. I joined a group for my final project. The project was to give recommend music artist concerts in a specific location. We had two design people and two business logic people. I bounced from designing and business to help out our team.
---

Well my last week with Angular-2 has been good. I joined a group for my final project. The project was to give recommend music artist concerts in a specific location. We had two design people and two business logic people. I bounced from designing and business to help out our team. We used five APIs for this project: [Firebase](https://firebase.google.com/), [Last.fm API](http://www.last.fm/api), [Google Geocoding API](https://developers.google.com/maps/documentation/geocoding/start), [Google Maps](https://developers.google.com/maps/) and [SongKick's API](http://www.songkick.com/api_key_requests/new).

So first we used the Last.fm API to get a user's top played tracks and return it in a array. Then with those top tracks we made a loop for each top track to give us 50 recommend music artist. On Wednesday we made too many API calls and they expired our Last.fm API key. So we got another one and this we were more cautious. Next we used songKick's API to give us concerts with those recommend artist. At first we were using the user's ip address for the location. We wanted to have a user insert a location to see other concerts in a different area. SongKick's API needed a latitude and longitude. Then we googled for an API to return latitude and longitude. Then we discovered Google's geocode.

Our group brain stormed an idea up to use Google's map API to show where the concerts would take place. I have to say their documentation is great. After our group meeting we jumped right into it. We got the map to display with 'pins' the address of the concerts.

By this point we polished up our project to present to our class. Our teachers give us five minutes to describe our project and demo it. They were very impressed on our design and how many API calls we made to make this project work.

So next is Rails, I've been counting down the days for Rails. I'm so excited to learn about Rails because it's that much closer to our internship. My brother and his partner have been helping with interviewing. I have never been through a real interview. But I'm making progress but yet I still have the mountain to climb.

Our project on Github: [Tune Trip](https://github.com/kftwotwo/tune-trip-kevin)
