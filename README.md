Development Resources
https://github.com/webprogramming260/.github/blob/main/profile/instructionTopics.md#readme

Website Name : Ohpug.com
1/31/2023
Commands to remember
➜  ssh -i ~/keys/production.pem ubuntu@ohpug.com
sudo vi Caddyfile

change security certificate using caddy to https
myfunkychickens.click {
   root * /usr/share/caddy
   file_server
   header Cache-Control no-store
   header -etag
   header -server
   }


startup.myfunkychickens.click {
   reverse_proxy * localhost:4000
   header Cache-Control no-store
   header -server
   header -etag
   header Access-Control-Allow-Origin *
}

simon.myfunkychickens.click {
   reverse_proxy * localhost:3000
   header Cache-Control no-store
   header -server
   header -etag
   header Access-Control-Allow-Origin *
}


http://18.221.114.145

# startup
Sketch of Website Application
https://ninjamock.com/s/6V6TVKx

1/27/2023

Elevator Pitch:

Why is it that the most unhealthy things taste the best? Maybe that doesn’t have to be the case. That's why we created Ambrosia. Now you can find food that is rated to be 1. Healthy 2. Tasty  3. Cost-Efficient and 4. Environmentally sustainable. For those who enjoy eating out or in, there are ratings for both. Not only will you find the best food, on so many levels, but you can order it at the touch of a button.  

Let’s help the world eat food fit for the Gods, but made for man, all while being good for the planet and the pocketbook.
You don't have to climb Mt. Olympus, just go to the Ambrosia app, or Ambrosia.com. 


Key Features:
Food recommendatoins. 

I am creating a merge conflict.
This is my edit on GitHub.

this is me changing the readme file on my startup project.
-Karl Nordgren

In this assignment I learned about pushing and pulling items to GitHub. I also learned about resolving merge conflicts.
