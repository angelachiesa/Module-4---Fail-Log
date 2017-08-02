# Fail Log for Module Four
##### July 31st - August 6th
------------
###### Previous Mistakes
One of last weeks mistakes was that I did was not correctly complete an exercise. I still went on and understood and learned how to do the exercise and received help on how to properly do it. I think this was a better approach rather than waiting for a response, because by the time I received a message, I knew how to do the tutorial, so when someone was able to explain it, I quickly redid it and saved time.

Turns out, I just forget to change it into the CSV when I uploaded the file. I had someone mention this in the slack group so it helped out a lot. I really appreciate that person's help.

###### Readings
For this week's annotations, I choose _Principles of Information Visualization_ which is in _The Historian's Macroscope: Big Digital History_ by , by S. Graham, I. Milligan, & S. Weingart. I choose this reading because I love learning about visualization representation and do it on a daily basis. I enjoyed this read because I got to learn about different graphs and ways of representing data. I even got to see some weird charts like the Cartogram and even learned the name of a geographic visualization called choropleth. I usually go with these visualizations for my projects so it was nice learning the term for it and more information.

# Exercise 8
###### Simple Mapping and Georectifying

For this exercise, I had to use mapwarper to take a historical map I found online and to warp it onto a more modern day version of the map. 

I had a lot of issues with this exercise as the map would just not load into Palladio. After 3 hours and asking for help in the group. I don't know what went wrong or why it would not load, but even after following instructions from Professor Graham, it wouldn't load as well. Unfortunatly, today is the only day I can submit before Sunday as I am leaving town tomorrow, I will just have to leave the exercise as it is. 

**Notes - How to Wrap Maps**
1. Go to Harvard World MapWarp, go to upload map and add in your map.
2. Click on 'rectify' and add control points and try to match up both screens as best as possible.
3. Go to export and copy the linkbase fomr Tiles (Google/OSM scheme)
4. Go to Palladio and upload a spreadsheet or csv
5. Follow this tutorial https://www.youtube.com/watch?time_continue=173&v=KgLrvcA8v_M
4. Remmeber to Replace /z/x/y with {z}/{x}/{y}
http://warp.worldmap.harvard.edu/maps/tile/6449/{z}/{x}/{y}.png

# Exercise 9
The exercise shows us to do scripted analysis. We write out transformations, which creates a program that we can use onto our data.

**Notes**
1. Click R Script
2. Create a new Directory
3. To connect to Git use (git config --global user.email "you@example.com"`)
4. Go under 'Tools', select 'Version Control', 'Project set u p', and click 'git'.
5. Go to the right side and under git click/tick ofof your files and click 'commit'
6. Go to your github account, and make a new respository; intialize it with readme.md
7. back in Rstudio, click more gearwheel on the git tab and select shell
8. $ git remote add origin https://github.com/YOUR-ACCOUNT/YOUR-REPO.git
$ git config remote.origin.url https://github.com/YOUR-ACCOUNT/YOUR-REPO.git
$ git pull -u origin master
$ git pull -u origin master
9. This now pushes everything to that

The screen goes into four panels. The top left is for writing your analytical script/code.
The bottom left is where the analysis takes place.
Top right is an environment pane which will show what you've created, your history, and git. Or other plugins etc.
The bottom right gives you preview of any plots or charts. 
>Reflection
I definatly like the idea of you being able to see an other screen of your files made unlike in commandline where you need to pull it up and everything looks the same. I found R studio easier to follow but perhaps it could of been just because I had already done commandline and had an understanding.
