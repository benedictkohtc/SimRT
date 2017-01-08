# The Overglorified Screensaver

This game has been heavily inspired by a particular indie title which shall go unnamed <sup>*plsdontsuemeIhavenomoney*</sup>. As such I take no credit for its awesome simple-to-play yet hard-to-master game mechanics and minimalistic design.

I wanted to build something that I myself wanted to play. And just to really push myself and see how far I could go. Everything you see here is pure html, css and javascript with JQuery.

This game is essentially an urban mass rapid transit builder and simulator. Be warned! You will never look at another railway map the same way again.

### How to Play

tldr: Deliver passengers by building train lines, decide how to deploy trains, don't let any station overload.

Passengers are represented by little symbols and will alight at any station matching their symbol.

You have 3 train lines and 5 trains available to you.

Stations are considered overloaded when they have more than 6 passengers waiting on the platform.

Stations will flash red when they are overloaded.

The game ends when any station is overloaded for more than 10 seconds.

**Building Tracks:** Click on grids to design your railway network, click again to confirm your network design.
**Removing Trains:** Trains will first proceed to the next station to drop off all passengers before being removed from the system.
**Destroying Lines:** All trains running on that line will automatically receive a "Remove Train" signal. A line has to be free of trains before you can destroy it.

### Game Bugs <sup>*thatwereturnedinto*</sup> Features
**1) Passengers will only make a maximum of 1 transfer.**

This means that passengers will only take a maximum of 2 lines to reach their destination.

*Passengers in this urban metropolis have high expectations of their transport systems. They expect to be taken to their desired destination quickly and efficiently*

**2) You may only extend existing lines on the end with the coloured block.**

The block represents the tunnel boring machine(TBM) used to create the subway tunnel. Remember that you can destroy existing lines to rebuild them from scratch.

*TBMs are sometimes left behind simply because it is cost prohibitive to excavate them out - fortunately it allows us to expand our subway network at will!*

## Live Version

https://benedictkohtc.github.io/WDI-Project1/
