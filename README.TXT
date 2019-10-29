I've programmed before, but never in Java. The things I'm doing here work, I would wager a fair amount they aren't the 
best way of doing things. 

At this early stage, I adjust the quantities of each type of creep by manually changing the number in an IF test. 
For example, "if(buildersCount.length < 6)" will maintain six builder/repairers in my main room. 

The second room I just started in. I sent a scout to a flag I placed to "see" the room, so the getObjectById would work. 
I ended up just hard coding the sourceId in the remote harvester/builders, but that will change before I open another room. 
But even that hard coded ID won't work unless you can "see" the room, so for now I need to keep a creep there at all times 
for the RH creeps to be able to find their way there upon creation.
