---
layout: post
title: '[Review] Leixen VV-898E 25W VHF/UHF Radio'
date: 2020-07-29 21:35:00 -0400
author: Michael
type: post
published: true
status: publish
---

### TL;DR:
#### Pros:
1. It does what it says on the box
2. Good audio reports
3. Three user-programable front panel buttons

#### Cons:
1. Cheap Build Quality
2. Suffers from intermod
3. Extremely poor rejection
4. Poor thermal design
5. Weird dual-bank memories

### Leixen VV-898E 25W VHF/UHF Radio
![](/assets/leixen-vv898e/front.png){: .center-image }

I've had this radio for over 6 months now, so I think it's time for a review. The Leixen VV-898(S/E)
radios come in an execptionally small package at 120x90x40mm it will fit almost anywhere in even
the smallest cars. The base model outputs 10W high power, and the S/E models output 25W on high
power, not to shabby for such a small package. This radio, for better or worse, also has a very
wide coverage range for RX as well as TX, 136-174MHz/400-480MHz. The display has both A and B
displays for monitoring two frequencies at once, as well as the option of displaying channel
name by name or frequency. Underneath the display are the P1/P2/P3 buttons which can be user
programmed for various functions. Additionally, the VV-898(S/E) is compatible with chirp!

On-air reports have been all positive. So far I've been told the radio sounds nice and clear. I've
read a few reviews online stating the microphone requires modification to be heard properly, however,
I have been using the radio stock without any mic problems. Maybe I simply got a good one out of the factory?

Unfortunately, that's about where the good news ends.

The build and finish of the radio is extremely cheap, almost makes a BaoFeng feel like a good
radio. The front appears to be cheap plastic, the remainder of the case is aluminum. There is
no heat sink on the radio, and there is a spot for a fan, but no fan is installed. I have not
yet opened the case, but I'd assume the aluminum shell is used to dissipate heat - and boy does it.
Operating on medium power (10W) VV-898E gets a tad warm to the touch by simply being on,
longer QSO's tend's to heat up the case quite a bit. And forget about using 25W for long, those
finals may just give out. That said, this is not the cheap mobile for those long winded Ham's
among us (which I can be totally guilty of myself at times :))

The dual watch feature is nice, however there is no indication as to which band a signal is
being recieved on. So that leaves the operator to guess. That's not so much of a problem if
you have a repeater on the A side, and 146.52 on the B side, because the repeater curtiousy
beep will be enough to determine the side. However if you have both sides on a repeater, or
both on a simplex channel, it can get confusing. Also, noticed I said 'dual watch' earlier,
yep, just like any BaoFeng, this radio does not have true dual receive. So if dual watch is
enabled, then which ever side gets a signal first has the speaker. This I find to be a major
disappointment, even the $23 UV-5R has an indicator on the screen as to which side is receiving.

Intermod, the VV-898E is plauged with constant intermod problems. I suppose it would be fine
in a fixed station, however as a mobile station, just about everything sets this thing off. From,
EZ-Pass toll booths, super market door sensors, etc. Rejection is a problem as well which I've
only noticed once or twice during the rare CB transmission to help out a Trucker, however I was
able to hear myself coming through very distorated (maybe it's time to make a band pass filter?).

The last pain point is really kind of a nit-pick, but should be mentioned - memories. It's listed
that the VV-898E has 198 channels, which it does. However, the channels are split between the sides,
band A has 99, and band B has 99. You can't simply program in 198 channels and access them from both
sides. This is kind of a bummer for me, but something I can live with. I'm not sure why Leixen went
down this route as the older firmware for this radio has one contiguous block. Also, Chirp as of 
20200521 does not yet properly support this firmware. There's still a [ticket open to add support](https://chirp.danplanet.com/issues/4069)
as of the time of this writing, the ticket also has a [module](https://chirp.danplanet.com/attachments/5237/leixen_dualbank.py) attached which does work.

#### Final Thoughts

Overall, it's not a *bad* first radio for the new ham, but it's not something I could recommend either.
Honestly, I should have spend a bit more money and picked up a better radio. I am going to replace this in
the mobile at my earliest convenice, but I'm not going to toss it in the bin either. I'll give it
a shot in the shack for a little while until I get something better there as well. Then, if it hasn't
given up the ghost yet, maybe have it do some shack APRS/Packet duty.
