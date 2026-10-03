Training data for a failed survev.io aimbot.
The idea was to train an OpenCV classifier to identify enemy players on the screen. A separate program would then automatically aim my cursor at the enemy player.   

I had ~500 training images and I manually labeled each one. After training, the classifier did moderately well. The sole problem was latency. The classifier had a lag of around ~200ms, which was far too slow for aimbot to be effective. 
