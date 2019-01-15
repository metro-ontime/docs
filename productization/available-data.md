# What data we have
- Each train has an ID that we can use
	- Is a Train ID Unique to a given train (always)
	- Does the ID have any metadata?
- Trains per line
- Average speed between two points that we can detect at
	- We can track how far the distance between tracking points
	- We have points that are randomized between stops
- We can track between what points the train stops (make inferences)
- Another data set measures the total number of taps per station
	- Might be real time
- We could potentially log predictions per station
	- Then we can think about figuring out how reliable they are
- We can tell when trains go offline

## Stretch
- Train Cars per Train - Maybe weight per station
- Tap into station and tap at transfer
- Compare trains between two stops speed (months apart)