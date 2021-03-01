---
layout: post
title: "Antenna Towers and Airports"
date: 20210228 22:00:00 -0500
author: Michael
type: post
published: true
categories: Projects
status: publish
---

So the days are starting to get longer and warm weather is around the corner. It's almost time to get
started on some outdoor projects. My list is long, but there's some fun projects in that list - like
antennas! Currently I've got the one antenna - the IMax 2000. It's a little on the low side at the moment,
about 12ft from the ground to the top of the bottom of the antenna, plus it's length of 24ft. I've been
wanting to get it up a bit higher, but I do live rather close to an airport. I remember from the
General Exam study - (G1B01) Maximum Antenna Structure Height - question below:

___G1B01 from the General License Course Section 1.3, DX and Details:___

_What is the maximum height above ground to which an antenna structure may be erected without requiring_
_notification to the FAA and registration with the FCC, provided it is not at or near a public use airport?_

Of course we know the answer (all ham's want to know how high they can go!), it's 200ft. But what about this
bit: _provided it is not at or near a public use airport?_. The study material isn't exactly clear on that,
you've got to do some digging. For most ham's, the worry of air traffic is minimal to non-existant, however
for this ham, I'm about 2200ft from the nearest runway. That's well within the "I need to worry about
this" range.

Ok before we go on...

**Disclamer: I'm not a Lawyer... This is simply my interpation... Your mileage may vary...**

So, with that out of the way, let's get into it.

## So... How high can I go, exactly?

That depends ... largely on how far away you are from the airport AND how long the nearest runway is from your
antenna location. Doing abit more digging, I found the statue outlining everything we need to know (caution,
legalize ahead): FAA Code of Federal Regulations, Title 14, Part 77.9(b). The legal text can be found here at
Cornell (other places as well, probably): [https://www.law.cornell.edu/cfr/text/14/77.9](https://www.law.cornell.edu/cfr/text/14/77.9).
I'll display it here as well, as of 28 Feb 2021 (but go to the source, as this post ages, the revelant info may change).

_(b) Any construction or alteration that exceeds an imaginary surface extending outward and upward at any of the following slopes:_

_(1) 100 to 1 for a horizontal distance of 20,000 ft. from the nearest point of the nearest runway of each airport described in paragraph (d) of this section with its longest runway more than 3,200 ft. in actual length, excluding heliports._

_(2) 50 to 1 for a horizontal distance of 10,000 ft. from the nearest point of the nearest runway of each airport described in paragraph (d) of this section with its longest runway no more than 3,200 ft. in actual length, excluding heliports._

_(3) 25 to 1 for a horizontal distance of 5,000 ft. from the nearest point of the nearest landing and takeoff area of each heliport described in paragraph (d) of this section._

OK... Let's put that in a bit more.... you know... normal people english...

If the nearest runway within 20,000ft is longer than 3200ft, your ratio is 100:1. If the nearest runway is less
than 3200ft and is within 10,000ft, the ratio is 50:1, and within 5000ft of a helipad, 25:1. Much simpler..

Now how about the ratio, this can simply be explained as for every 100ft of distance to the runway your
antenna structure is, you're allowed 1ft of elevation. Where they got those numbers from, the world may never know,
much like how may licks it takes to get to the center of a tootise roll pop :).

## Data Gathering and Math

So, Now we need to know how long the runway is that is nearby. For me, that's about 6000ft & 8700ft. How to I know this, I
googled it. Pulling up the my local airport runway lengths are on Wikipedia, I'm sure other airports are as well. To find
out how far you are from the runway(s) in question, Google Maps has a 'draw a line' feature which will show how far, in a
straight line, something is between two points. Using that, I found I am about 2200ft away, rather close.

OK, so we know the length of the runway(s), and how far we are. Let's do some math. Both runways in my example are more
than 3200ft, so I'll have to use the 100:1 ratio (which sucks). The math:

`2200 x .01 = 22ft`

What! 22ft! That's IT! My Imax is 24ft, and would technicly need a permit mounted at ground level... But.. luckily there's some
wording in the FAA rules which we can use to work around this number (quite a bit)

## Too close, for really anything, but there's always execptions

In FAA Code of Federal Regulations, Title 14, Part 77.9(e), there's an exception to this hight issue above.

_(e) You do not need to file notice for construction or alteration of:_

_(1) Any object that will be shielded by existing structures of a permanent and substantial nature or by natural terrain or topographic features of equal or greater height, and will be located in the congested area of a city, town, or settlement where the shielded structure will not adversely affect safety in air navigation;_

Basiclly, if you have trees/tall buildings/hills/etc, AND you live in the suburbs (as I do), you can use those as the max height.
I should also note they do not say how close you need to be to said execption structure. In my humble opinion, I recommend using
the trees as the max - that's what I'll be using, and they tend to be rather premanent..

Well, how do you find out the height of a tree. There's a lifehacker article for that [https://lifehacker.com/is-there-an-easy-way-to-measure-the-height-of-a-tree-5875184](https://lifehacker.com/is-there-an-easy-way-to-measure-the-height-of-a-tree-5875184).
Essentially, take a stick the lenght of your arm, hold the bottom of it with your hand and hold it straight out and up.
Line up the top of the stick with the top of the tree, once done, your feet should be about as far away from the base of
the tree as it is tall (if you remember geometry, you'll realize you've just made a right triangle). That hight is antenna
structure limit.

## Closing Thoughts

All that and I still don't know how high I can go.. Waiting on the snow to melt and for the weather to get a little bit warmer.
However, as a ball park guess, I'm thinking I'll be able to do 40-50 feet, which is about what I was looking for anyway. So at
the end of the day, I could have just done what I wanted, but better to play it safe - nobody want's a knock on the door from the FAA.

Src: [https://hamradioschool.com/g1b01-maximum-antenna-structure-height/](https://hamradioschool.com/g1b01-maximum-antenna-structure-height/)
