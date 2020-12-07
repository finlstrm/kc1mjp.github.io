---
layout: post
title: "[Project] Digital Mode Interface - Rev Alpha"
date: 2020-12-05 22:00:00 -0500
author: Michael
type: post
published: true
categories: Projects
status: publish
---

While I've been waiting to upgrade to General, and saving for more radios, I've
been looking for ways I can expand what I can do with what I have. Discovered
recently that Technicians absolutely do have digital mode(s) privileges on 10
meters. 

![](/assets/posts/band-plan-10m.png){: .center-image }
[Band Plan Key](/assets/posts/band-plan-key.png)
{: .center-text}

The above are screen grabs from the [ARRL Band Plan](http://www.arrl.org/files/file/Regulatory/Band%20Chart/Band%20Chart%20-%2011X17%20Color.pdf).
When interperted by the *Band Plan Key* you find that between 28.000 and 28.300,
Novice and Technician Class Licensees have privileges for *RTTY* and *data*.
Initially I read that as RTTY and *CW*, boy was I wrong. *Data*, is in reference
to any data mode, such as the popular FT8, JS8Call, as well as others. So that
got me thinking, what to I need to get setup?

Software was easy, [WSJT-X](https://www.physics.princeton.edu/pulsar/k1jt/wsjtx.html)
was a simple apt-get away (Debin LHS FTW!). But what about hardware? That's the
tricky part - the rig I'm currently using is a Kenwood TS-130s. It's a mighty fine
rig and I love using it - but there's no way to interface it with any sort of digital
modes. It was made between 1980-198x, about 30-40 years ago - not suprising. So what
do I do now, sell the radio I just got and buy something with a proper interface? I
suppose that's what some Hams would do, but what's the fun in that? Let's get building!

I started out with with grand plans, but for Rev A, let's take the KISS approch (Keep it
Simple Stupid). So I'm starting with something simple that works.

Starting simple, we're only going to need a usb sound card, 3ft 1/4" to 3.5mm mono cable,
3ft+ lenth 3.5mm stereo cable (lenth doesn't matter, were going to cut it), one female
microphone plug (my radio is a 4 pin), soldering iron and solder. All I had to buy was the
sound card and cables, had the rest.

The Mono cable, can plug straight from the headphone out on the front of your radio, to
the mic-in on the soundcard. Just make sure the volume is turned down before you plug it
in.

Next, I cut the stero cable the a little longer than the mono cable, and stripped the
outter insulator exposing the sheild and two audio lines. I cut the red one out - that's
the *right* channel, I required the *left* channel. I then followed the Kenwood manual -
Pin 1 is the mic feed pin, so I soldered the left channel there, and Pin 4 is the mic
sheild or ground, so the cable's sheild/ground got soldered there. That's my radio, if
you've got a 80's era Kenwood, this will probably work, regardless RTFM. I then buttoned
it all up, configured the soundcard and off to the races! 

But wait! There's more, noticed I left pins 3 and 4 empty. Don't we need those for PTT?
Well, yes, but that will come later. Here we are relying on the radio's VOX. So connect
your dummy load, and tune the vox until it reliablly keys and unkeys the radio with the
desired digital mode. I'm not going to go into how to set VOX or digital mode tune functions,
every radio is a little different, and there's plenty of digi mode how-to's out there.

![](/assets/projects/digimode-interface/RevA-Radio-Connectors.jpg){: .center-image }
![](/assets/projects/digimode-interface/RevA-Radio-Connected.jpg){: .center-image }
![](/assets/projects/digimode-interface/RevA-Computer-Connected.jpg){: .center-image }

There you have it, I've been using it on FT8. Works great -> [KC1MJP CloudLog](https://app.slashetc.us/cloudlog/).
I haven't made a ton of contacts as of this post, as I now get to learn all of the in's and
out's of FT8, and hopefully not making the seasoned vets mad in the process.

In the next Rev, I'm going to add some isolation, as well as PTT triggering via
RS-232 Serial. Maybe even some RX/TX LED action. We'll have to see how that goes,
stay tuned!

73, de KC1MJP

**Parts I Used**:
* Sabrent USB External Stereo Sound Adapter: [https://amzn.to/3mM25ip](https://amzn.to/3mM25ip)
* Hosa CMP-303 3.5 mm TS to 1/4" TS Mono Interconnect Cable: [https://amzn.to/33L65rG](https://amzn.to/33L65rG)
* Monoprice 6ft 3.5mm Stereo Plug/Jack M/F Cable: [https://amzn.to/3mT0R52](https://amzn.to/3mT0R52)
