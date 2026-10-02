# Dead-Reckoning

<aside>
💡

The process of calculating the new position of an object by using its previously determined position and incorporating estimates of speed, heading/direction and elapsed time.

The idea in itself is simple. if i go in this direction for this distance, i must be right here. if i move from my starting point for 2KM north, i must be 2KM north of starting point.

</aside>

<aside>
💡

How It works: 

Dead reckoning starts from a known reference position, calculates the distance traveled using speed and elapsed time, uses the heading to determine the direction of movement, updates the position, and then repeats this process continuously while accounting for changes in heading.

</aside>

<aside>
💡

Dead Reckoning in itself is prone to errors that accumulate over time due to various external factors and that is why they are almost never used alone. the longer you navigate solely relying on Dead reckoning, the greater your navigation error would be.

</aside>

<aside>
💡

For example, In automobile  navigation systems, a dead reckoning navigation system, the car is equipped with various sensors that measure a lot of things from wheel circumference to steering direction etc. The navigation system then uses a KALMAN filter to combine these sources of information to estimate the vehicles position, velocity and heading more accurately even when a particular sensor data like lets say a GPS is week or temporarily unavailable.

</aside>

<aside>
💡

Applications:

- Maritime Navigation: backup technique for sea navigation in open seas should incase GPS fails.
- Autonomous vehicles: employed in self driving cars when GPS signals are blocked; robots navigating indoors where GPS signals are not available. in such scenarios they use Dead reckoning with SLAM.
- Gaming and Virtual Reality: used to estimate the Position of a player in a virtual MORPG and MMORPG’s
- Aviation navigation: used  by planes when flying in GPS degraded environments such as polar regions or during electric warfare scenarios
</aside>

References:
https://www.land-navigation.com/dead-reckoning.html
https://www.anellophotonics.com/dead-reckoning-guide
https://en.wikipedia.org/wiki/Dead_reckoning
