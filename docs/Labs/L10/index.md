# L10- RC2 Sliding Fit

## Objective


## Research and Planning  





RC2 fits are used in many applications. Like automotive components for shafts and bearings without friction or machinery like conveyor belt systems that need to turn easily but not move freely in and out. Any application that allows free turning but not excessive assembly and disassembly.  


In my research I found that resin prints always shrink, and by different amounts depending on the prints size, the resin used and the printer. This means that it makes the most sense to represent shrinkage as a percentage. My resource used trial squares and measuring averages and the shrinkage offset, and they found that a factor of 0.96% should be used.  




## CAD Design  

Before I began modeling, I wanted to confirm the shrinkage with a test square in the printer. I found that the part actually expanded by 5%. This was confusing but I thought it may have been something to do with the clear resin, but it may have also been that I did not cure it long enough because this ended up being an error. However I used this 5% expansion in my design, since this means I made the hole clearance larger than necessary it actually worked out for the best.  

For my design, I decided to make a small tool that can be used to take measurements of items that can't be reached with a caliper. Meaning this print can be pressed onto something and stay put due to the RC2 fit, and then be measured with the caliper in that somethings place.  

I used 0.3in for a nominal size, and applied the RC2 tolerances from the machinery's handbook to the hole and shaft. Those being 0.0004in for the hole and 0.00085in for the shaft. Then I added a percentage multiplier of 1.05 or 5% increase to account for expansion.  




## Communicate

