---
layout: post
title:      "Rails Project"
date:       2018-08-09 11:48:59 +0000
permalink:  rails_project
---


For my Rails project I focused on beer... again. Mainly because I like beer, but also because I like beer. Starting the project was a real struggle, per usual. While I was told about virtual box and its benefits I was never really guided towards setting it up post-sinatra project completion. I started working on my project in the IDE and soon found that it was impossible to complete. I was able to set up the bare bones of it with some trying and testing efforts. I had my database and activerecord models associated to their respective tables. When it was time for me to start using the server to debug I was unable to access it via windows with the IDE. No matter what I tried the web browser would not be able to access my App. That being said I eventually got virtual box set up and it was some what smooth sailing from there. 

I feel like the way I set up my models and their associations might have not been most conducive to what I was trying to do. My new recipe's view is fairly sloppy and the logic in the controller isn't much better. I was unable to figure out a way to validate my nested ingredients models and had to MacGyver my way to a working solution. I essentially created a method that would take the nested attributes hash and set the recipe id after the recipe was saved. I would then checked to see if the recipes ingredients array was equal to a specific count. If It was not I would clear the hash and put out a flash message telling the user to basically fill out all ingredient fields. 

fin
