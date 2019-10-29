I started a few days ago playing with the screeps.com live demo simulation. I noticed it on Steam on sale so
I bought it a few days ago for 7 bucks. It's WELL worth it to me, I'm really enjoying it and
it's motivating me to get better at java. I've programmed before, but never in Java. The things I'm doing here work, 
I would wager a fair amount they aren't the best way of doing things. This is about 10-15 hours of programming, looking at it,
then trying something different to tune things more. 

At this early stage, I adjust the quantities of each type of creep by manually changing the number in an IF test. 
For example, "if(buildersCount.length < 6)" will maintain six builder/repairers in my main room. 

The second room I just started in. I sent a scout to a flag I placed to "see" the room, so the getObjectById would work. 
I ended up just hard coding the sourceId in the remote harvester/builders, but that will change before I open another room. 
But even that hard coded ID won't work unless you can "see" the room, so for now I need to keep a creep there at all times 
for the RH creeps to be able to find their way there upon creation.

I'll probably rewrite the way I find where everything is, it seems inefficient to have a hundred bots doing searches so 
I'll likely figure out how to find everything once each tick (building sites, things to repair, things to harvest, etc)
then store it in a memory array to keep it persistent and parse out what I want for each type of bot. 
