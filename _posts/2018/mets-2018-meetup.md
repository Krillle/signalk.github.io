---
title: Community Meetup at METS 2018
layout: post
author: Kees Verruijt
email: kees@signalk.org
gravatar: https://avatars3.githubusercontent.com/u/1608058?v=3&s=64
status: published
publishDate: 2018-11-22
---

**TL;DR: this year’s Signal K meetup at METS saw the highest turn-out yet. We had a good meeting, and for the first
time ever actually agreed to set-up various working groups to “get things done” on security, better documentation &
Signal K organisation structure.**

On Tuesday 13 November we held the traditional yearly Signal K meetup during METS. This year we were lucky to be
sponsored by [Victron](https://www.victronenergy.com) who very kindly provided one of their two meeting rooms. We had
to be a little cheeky as there were so many people that we had to swap the small room originally allocated to us for
the big one, and ask all Victron employees to cram into the smaller room! The turnout was our largest ever with a good
contingent from the USA, but logically the other participants flew in from closer by, with various European countries
represented as well as 5 locals. New commercial participants in the session included
[CrewFellow](https://www.crewfellow.com) / [SolveIt](https://www.solveit.nl) and [IoT.bzh](https://iot.bzh).

![Thanks Victron!](/images/posts/mets2018/left_side_s.jpg)

After the introductory round which established that the attendees were a cool mix of old timers, people we have met
online regularly in the last two years as well as representatives of two new companies with an interest in Signal K.

The meeting started with various people reporting on the “State of Signal K.” Although we are far from done, and
probably never will be, a lot has actually happened since we last met a year ago. We are now at v1.2.0 of the data
standard, reflecting that we had two minor corrections and a number of clarifications and extensions of APIs since
v1.0.0.

![Ben Ellison, Fulup Ar Foll, Teppo Kurki, Alex Kritikos, Thomas Sarlandie](/images/posts/mets2018/right_side_s.jpg)

Work on the Node server implementation is proceeding at a rapid pace thanks to Scott and Teppo -- a start was made with
security, the admin UI was added, and hundreds of pull requests were accepted. OpenPlotter has now elevated Signal K to
a “primary support” status. As to manufacturer take-up, we have been blessed by Victron coming in as a result of METS
2017 and making an excellent contribution by adding Signal K support to their Venus GX device. Venus GX actually runs
an open source (linux) stack, based on the BeagleBone Black, so it is a great system for tinkerers.

Next was a (long) brainstorm about where the group felt the most urgent need for enhancements. Top of that list was
security, closely followed by better documentation (separating the specification from APIs, documentation on what
constitutes a server, consumer, etc). It was also decided to start working on promoting specification compliance and
professionalising the Signal K “organisation” itself. To actually Get Things Done™, we organised “working groups” to
tackle the various enhancements. It is great to see a wider audience taking up responsibility!

The Security workgroup consists of Theresa, Teppo and/or Scott, Romain/Arthur (IoT.bzh), Alex and Charlie. If you want
to help out, feel free to [join Slack](http://slack-invite.signalk.org/) and join the #wg-security channel.

Various (recent) Signal K community members pointed out that there are issues with our current documentation set. It is
not clear what’s what for newbies and needs better separation between APIs, non-spec APIs, definitions (what
constitutes a minimal server, a client, etc.) The workgroup tackling this problem consists of Tim, Alex, Clément
(IoT.bzh), Thomas, Charlie and Matthijs (Victron). The group meets in #wg-documentation.

![Discussing Documentation](/images/posts/mets2018/docs_discussion_s.jpg)

Promoting specification compliance is still in need of volunteers that want to work on improving this. We need a set of
rules/guidance for server/client implementers and a test suite to test specification compliance. Obviously, there is a
relationship with documentation here! An alternative idea that was suggested was to have the rule that a conformant
implementation needs to implement a minimal set of functionality and if it is interoperable with two or three other
(commercial or open source) implementations it can claim to be Signal K compatible. Head to the #wg-compliance channel
if you would like to contribute.

Another issue voiced was “what is the core group and what is its significance?” A short history lesson was provided how
Signal K got started by five people who “met” at a Github issue and started Signal K together. The core group is not
equivalent to the typical “dictator” found in some open source communities, it is just the group of people that were
there from the start and happen to have RW access to Github. We decided to dissolve the core group and come up with
something better. A workgroup was organised with Fabian, Thomas, Stephane (IoT.bzh), Tom, Michael and Martin. They meet
on #wg-structure.

On the evening of the meetup most people met for drinks at a local brewery. Food was enjoyed and beer consumed, but
most importantly everyone had a great time. We obviously won’t share any details, because what happens in Amsterdam…

Please join us next year to find out more!
