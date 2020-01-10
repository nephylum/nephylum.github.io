---
layout: post
title: Symphinity - Analyze a song and find more like it
subtitle: A Data Science project in 4 days
---

This week I'm publishing my first team project [HERE](https://spotify-song-suggester.github.io/Marketing-Page-SSS/)

As an assignment for my Data Science class at Lambda School, we were given 4 days and a team of 11 people to make a project. This is my first project working with a team, and I am very proud of what we have accomplished.

After you sign up and login, you are able to search through a database of over 600,000 songs.
![Symphinity Search Page](https://cdn-images-1.medium.com/max/1500/1*_A5F6yJR08Tovr-wKr7QYw.png){: .center-block :}
 
 After a search is made the app will display a visualization that the Machine Learning team worked on.
 
![Song Details Radial Graph](https://cdn-images-1.medium.com/max/1500/1*3gKwhaRCJXzm9F5DApiqrw.png)

We got our data via a Spotify API. A Flask App deployed on Heroku would use a KNearest Neighbors model to get a selection of the 10 most similar songs, as well as a visualization that was encoded into Base64 for bandwidth considerations.

My specific role was to build and deploy the Flask app. I worked closely with my classmate Isaac Lopez, and was able to deploy on Heroku. (you can access what I did directly [HERE](http://spotify-song-suggestor.herokuapp.com/).

