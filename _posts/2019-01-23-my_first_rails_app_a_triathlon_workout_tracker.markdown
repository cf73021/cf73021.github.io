---
layout: post
title:      "My First Rails App, a Triathlon Workout Tracker"
date:       2019-01-24 04:54:38 +0000
permalink:  my_first_rails_app_a_triathlon_workout_tracker
---


I started building this application with the idea that I would be able to use it to track very, very basic triathlon training activities. I was very excited to get started expirementing with all of the features that Rails had to offer.

I was pleasantly surprised to find that for every issue and problem I ran into, a google search sent me to  resolution that brought me to the next thing. Lets get started with explaining how this works, and some of the complications I ran into.

First, a user can log in, log out and register, courtesy of the functionality brought to the app by the Devise gem. Users can also sign in using Facebook, thanks to the OmniAuth gem. I had to do some extensive research to find out how to get both Devise and OmniAuth to work together and allow a user to log in, and be registered as logged in regardless of which method they chose.

Next, a user needs to select a sport. I display a link to the sports index page only after a user is logged in, I was able to do this using the is_logged_in functionality offered by Devise inside of a navigation layout that I render on every page.

After that, there is a basic workflow that involves them choosing the workout type and workout that they wish to complete, or create their own workout, which will be saved and added to the workouts list for use in the future. 

After a user chooses a workout, they are asked to click the "do workout" button, and input their perceived exertion on a new page. This value is saved, and the user is finally redirected to their workouts page, which is a nested resource page to ensure that the user only eses the workouts related to them.

One thing I can add in the future will be the deletion of workouts, which is just occurring to me now, as I write this!

Regardless, this project has really boosted my confidence using Rails, I feel that a LOT of the concepts that before were merely floating around in my head have become more concrete out of necessity. I am looking forward to completing more projects using Rails in the future.


