# SimRT

This game has been heavily inspired by a particular indie title which shall go unnamed <sup>*plsdontsuemeIhavenomoney*</sup>. As such I take no credit for its awesome simple-to-play yet hard-to-master game mechanics and minimalistic design.

I wanted to build something that I myself wanted to play. And just to really push myself and see how far I could go. Everything you see here is pure HTML, CSS and Javascript with JQuery.

This game is essentially an urban mass rapid transit builder and simulator. Be warned! You will never look at another railway map the same way again.

Note: In its current form, gameplay can be quite punishing. You may wish to disable the lose condition so as to fully explore the complete depth of the game at leisure. You can do so by clicking the "You Didn't See Anything" button at the bottom of the build menu, followed by the "Lose Condition" toggle.

### How to Play

tldr: Do not let stations become overloaded. Deliver passengers by building train lines and deploying sufficient trains. Additional stations are added over time.

###### Resources and Capacities
You have 3 train lines and 5 trains available to you. Each train has a capacity of 6 passengers. Each line can hold an unlimited number of trains. Trains do not collide with each other.

###### Stations
Stations are represented as large symbols. They are considered overloaded when they have more than 6 passengers waiting on their platform. Stations will flash red when they are overloaded. Additional stations will be generated as the game progresses.

###### Passengers
Passengers are represented as small symbols. They wish to alight at any station matching their symbol. They are randomly and periodically generated.

###### Lose Condition
The game ends when any station is overloaded for more than 10 seconds.

###### Lines and Tracks
You have 3 lines available to you, they are each represented by a different colour. Once built, lines can only be expanded from the 'end of the line', this is represented by the solid square block. An individual line cannot be forked into separate paths. Currently track looping is not supported. Lines can intersect or run parallel with each other with no risk of collision.

###### How to Build Tracks
Click "Build Line" from a respective line. New lines can be built at any location, existing lines can only be expanded from their end point (represented by a solid square block)  
Click a series of grids to trace out your desired railway path. A construction barrier will show where you have planned to build so far. Tracks can go diagonally.  
When ready, click confirm track locations.

###### Deploying Trains
Trains always spawn at the start of their line.

###### Removing Trains
Trains will first proceed to the next station to drop off all passengers before being removed from the system to be added into the resource pool. You may then redeploy it to another line.

###### Destroying Lines
All trains running on that line will automatically receive a "Remove Train" signal. A line has to be free of trains before you can destroy it.

### Game Bugs <sup>*thatwereturnedinto*</sup> Features
**1) Passengers will only make a maximum of 1 transfer.**<br>
This means that passengers will only take a maximum of 2 lines to reach their destination.

> *Passengers in this urban metropolis have high expectations of their transport systems. They expect to be taken to their desired destination quickly and efficiently*

**2) You may only extend existing lines on the end with the coloured block.**<br>
The block represents the tunnel boring machine(TBM) used to create the subway tunnel. Remember that you can destroy existing lines to rebuild them from scratch.

> *TBMs are sometimes left behind simply because it is cost prohibitive to excavate them out - fortunately it allows us to expand our subway network at will!*

## Live Version

https://benedictkohtc.github.io/SimRT
