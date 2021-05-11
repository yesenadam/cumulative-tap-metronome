# Cumulative Tap Metronome

### Bash script to find the tempo of your key taps

Used to find the tempo of a piece of music. I tried a couple of android apps, but the tempo number kept jumping around—it was hard to get a precise figure except by guessing. This script uses the total time, not just the time in between each tap. Keep tapping the tempo, and after a dozen or so taps the number stops changing and you can read off a fairly precise figure, to one decimal place.

Put `tap` in a folder in your bash PATH and `chmod +x top`. Then in bash type `tap`, tap in tempo until the tempo number settles down to a stable value. Ctrl-C to quit.

### Requirements

macOS and some other systems will need to install `gdate` from GNU coreutils. Linux and some other systems can use their existing `date`. 
