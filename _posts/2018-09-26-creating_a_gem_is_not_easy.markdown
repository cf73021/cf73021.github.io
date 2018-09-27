---
layout: post
title:      "Creating a Gem is not easy..."
date:       2018-09-27 02:05:31 +0000
permalink:  creating_a_gem_is_not_easy
---


So I learned recently that creating a ruby gem is not a walk in the park. When I first saw that I had been given this task as an assignment, the gravity of it caused me to close out of the curriculum and no re-open it for 3 days. I had no idea where to start!

Eventually I worked up the nerve to start experimenting and poking around with different code samples. I sat down and watched the intructional videos provided to me, and finally I opened the repo given to me that was created by a previous student. Getting my hands dirty in the code written by one of my predecessors proved to be the most effective way for me to build confidence and start making solid progress.

Piece by piece, I began creating my gem. My first real road bump was in getting bundler to run properly. It took me about 2 full nights of after-work coding sessions, head buried in the laptop, while ignoring friends and the world around me. Eventually I was able to crack it after some heavy googling and poring over the previously mentioned github repo from the previous student.

My first iteration of this project involved creating a scraper that would go to HBO.com and tell the user all of the available movies. This was unsuccessful, because I could not find a way for Nokogiri to play nicely with the names of the div's used on HBO's website. The divs's they were using had names like "div_one/ofthree--byfour". I am assuming something about that combination of symbols was throwing Nokogiri off, but I could not find anything on the internet to help me along. Faced with no other option, I switched websites to ESPN and decided to create a scraper of the featured articles on the home page.

This proved much more successful, and soon I was able to generate the top 10 articles featured on the ESPN website by running a simple program. The moment that it first worked I was taken aback by how cool the entire thing was, I really give most of the credit to whoever created the Nokogiri gem, as that is where the real magic was happening, but still - it felt great to be involved.

Finishing this gem is easily the biggest accomplishment I have to date involving Ruby and Object Oriented Programming, and while it is a simple program, I am nonethless proud to call it mine.
