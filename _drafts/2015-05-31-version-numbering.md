---
layout: essay
title: Liturgical Version Numbering
summary: "It's about the music, not your creativity."
---

### The Hymnal

My first reaction upon becoming acquainted with _The Hymnal 1982_ was the thought that I was born that year. Since I know hymnals take a little bit of time to assemble and publish, I couldn't help but realize that the hymnal sitting in the pew of almost every Episcopal parish didn't have a single piece of music written within my lifetime.

It isn't so much that I specifically object to a 30-year-old hymnal, or to traditional hymnody. I think the bulk of the music we sing on a Sunday should be music from previous generations, but... not a _single piece of music?_

In all honesty --- as a church musician I don't think this is really all that big of a deal. Additional musical resources have been published, and I'm perfectly comfortable including more recent pieces of music from almost any source into a printed worship program.

What bothers me about it, I think, is what it communicates. The cover of the book communicates that church music was _fixed_ at some specific point in the past --- as it happens, the year I was born. 

To the generation coming up behind me, 1982 might as well be ancient history. Ronald Reagan. The Cold War. Atari. The Hymnal. Things you learn about in a history class. Things that have nothing to do with today.

Anyone who knows anything about Episcopal Church music knows that the _1982_ replaced the hymnal of 1940, which bore the apparently timeless cover title of simply _The Hymnal_. Before that was a hymnal in 1916. So our hymnal production cycle is some period between 24 and 42 years.

I see two problems with that. The first is that this is much too long a period without substantial change. The second problem is that a new hymnal is a _new hymnal_. 

An entirely new work. Not an update. A new work.

And if _Wonder, Love, and Praise_ is a "supplement to The Hymnal 1982," what is its status if there were to ever be a new primary hymnal?

And what is the relationship between the 1982 and all the other additional hymnals the church has published? Are we to assume that African America music, or music written by women, or music in Spanish is _essentially_ an unneeded add-on?

### The Calendar

As the Church prepares for General Convention, discussion about the latest proposed sanctoral calendar, _A Great Cloud of Witnesses_, is making the rounds among the liturgigeek community.

Here's a series of impertinent questions:

Would _A Great Cloud of Witnesses_ replace _Holy Women, Holy Men_? Or would it replace _Lesser Feasts and Fasts_?

What exactly is the status of _Holy Women, Holy Men_? If _A Great Cloud of Witnesses_ ends up replacing _Lesser Feasts and Fasts_, what of _HWHM_? And why isn't the new book called what it actually has become? Will it be called _Lesser Feasts and Fasts_ eventually? Will the changes made there be eventually worked into a new version of _LFF_?

And, since every copy of _LFF_ I can find has a year attached to it, how am I supposed to know which year is the most current one? 2006 seems like a long time ago to me, but what do I know?

Now, I'm aware that any _expert_ on these things knows the answers to all these questions. But what about normal people in normal parishes?

### Book of Occasional Services

I recently got my hands on a _Book of Occasional Services 2003_. My first thoughts?

_That was a long time ago. I wonder if there's a more recent edition._

Also...

_Twelve years and the Rites of Initiation still haven't been implemented in most parishes._

...but that's a whole other issue.

When and if General Convention revises this book, 

### The Prayer Book

Thankfully, the 1979 _Book of Common Prayer_ doesn't put the year on the cover. Unlike the Hymnal and other resources, the Book of Common Prayer is primarily thought of as a single, subsisting _thing_, with a series of versions. Not a collection of independent items.

But there are weird versioning issues here as well.

I have, on my desk at the moment, three Books of Common Prayer that look, at first glance, to be basically identical.

One of them is the _Proposed The Book of Common Prayer_, printed in 1977. Another is the typical 1979 edition (printed when? I don't know). The third is an edition printed in 2007, with the Revised Common Lectionary (with no explanation about the two different "tracks" in the Post-Pentecost Season... _but whatever_).

And what of _Enriching Our Worship_? Is it, in essence, a "supplement" to the BCP, the way WLP is a "supplement" to the Hymnal? 


### The Common Problem

From my perspective as a technologist and project manager, it seems to me that we have a __version control problem__.

When you talk about some specific edition of a specific resource, how does anyone know what you are talking about? The "Proposed" version. The "Draft" version." The "Official" version. The "Revised" version. The "2006" version. 

How does someone just coming up to speed figure this stuff out? (Or do we, you know, not want that...?)

If there is a change from one edition to the next, where is it tracked?

Why isn't there one single place you can point to and say, "There --- that right there is the current official text."

Why is "The Calendar" called (at least) three different things? And what is the relationship between those things?

### Bad Language leads to Bad Process

The words we use for this stuff do not make what we are doing clear. This inevitably leads to confusion. (How many times have _you_ explained, or had explained to you, the fact that _HWHM_ isn't the official calendar?)

Moreover, it is both a symptom and a cause of a process that is inherently non-iterative, opaque, slow, and mired in the publishing cycle of a pre-digital age.

### A Proposal

If we approached resource publishing the way (good) software developers approached the development and release cycle, most of these problems would simply _go away_.

#### Version Numbers

Rather than naming releases by their year, which makes everything sound old and dated (remember Windows 98?), why don't we give version numbers to everything?

The current (1979) Book of Common Prayer is the fourth American BCP. I propose we refer to this as BCP4.

The current hymnal is the third (I think?) official churchwide Hymnal. It is the Hymnal 3.

And so on.

#### Semantic Version Numbering

But we can do better than plain old version numbering. We can adopt _semantic versioning_.

Semantic version numbers have three part, and look like this:
v 3.4.1

The first number is the _major_ version number, the second is the _minor_, and the third number is the _patch_.

This is really quite simple:

When a new, major version is released, you "bump the major." 

Moving from the 1928 to the 1979 was a major version change. (In software parlance, you bump the major when the new version is no longer backwards compatible.)

When minor features are added, bugs fixed, or other non-breaking changes are released, you "bump the minor."

The incorporation of the Revised Common Lectionary into the 1979 BCP would constitute a minor-version release. So the current BCP is 4.1.

When small changes --- usually bug fixes --- are released, these are called patches, and are identified in the third number. 

I'm not sure if there is a distinct need for patch numbering in liturgical resources, but maybe if we had it available we could get things done faster, knowing we could fix typos if needed.



#### Alpha, Beta, Release Candidates

Rather than a seemingly random series of "drafts" and "proposals" and "proposed drafts," we could follow the software development naming convention:

 - alpha --- An internal, first try.
 - beta --- A public test.
 - release candidate --- Your pretty sure this is the one.

There can be several release candidates. They get numbered rc 1, rc 2, and so on.

For liturgical books, I'm thinking the complete a-b-rc sequence would only really need to be followed for new major versions. For minor versions, we could skip straight to release candidate out of committee.

#### Its okay to abandon versions

The Calendar. Oi.

Let's call the original edition of _Lesser Feasts and Fasts_ v 1.0.

There have been a few revisions to it, parallel to the work on HWHM and AGCoW. These should be 1.1, 1.2, and so on.

_Holy Women, Holy Men_, if it was intended to be a replacement to _LFF_, should have been called LLF v2.

It had an Alpha, a Beta, and Release Candidate, but it hasn't been adopted. Work shifted to _A Great Cloud of Witnesses_. You know what that is? LFF v3.

It is currently in the public beta. Maybe it will be released as 3.0. Maybe not. Maybe there will simply be more minor versions of v1. Maybe the whole project will be scrapped and work will commence on v4. 

We don't have to keep coming up with clever titles every time we want to revise something. Or even if we want to change it completely. A major version number signifies that the whole thing is new, but is in continuity with the thing that came before it.

#### Version Control and Diff Tracking

If the BCP and other materials were kept under version control, in plaintext (or Markdown) files, with a source control tool like Github, the process of working on a new edition, or even minor improvements, would be much more transparent and open. 

There could be public discussion about each point, each change. Each decision, each choice, would have a URL --- you would know who was ultimately responsible, and you could follow a train of thought from the initial idea to its final form. 

Anyone who was interested could help and contribute in one form or another, giving a wide-ranging sense of ownership and buy-in. 

Anyone wanting to see how something changed could view diffs between versions. If you wanted to know who changed it, and who accepted the change, you could look at the pull request. If you wanted to know why it changed, you could look at the issue tracker. If you think another way is better, you could write your own version of a file and submit a pull request --- maybe it will get accepted and maybe it wouldn't, but at least no one is systematically shut out of the process.

#### More Frequent Releases and Parallel Versions

The change from BCP 3.2 (1928, rev. 1945) to BCP 4.0 (1979) wasn't completely smooth in a lot of places. There were a number of transitional releases and resources to ease people into it, but ultimately there was still some _specific moment_ when BCP 3 was officially deprecated and further support was dropped.

Perhaps this could have been avoided if there had been a 3.3, a 3.4, and so one, making small changes, until the need was felt for a more complete revision. At the same time, perhaps support (which means continued tweaking and incremental improvement) could have been retained for BCP 3.

Perhaps there wouldn't have needed to be a Rite I and Rite II, but rather a BCP 3.x and BCP 4.x with remarkably convergent ritual but two different language registers. Perhaps people would have felt comfortable adding a BCP 4 service alongside their BCP 3 service, and that would have made people less uncomfortable with the new edition.

Also, those choosing to retain the use of BCP 3 wouldn't be trapped in 1928. BCP 3 would continue to evolve until it died off naturally (people voluntarily stopped using it, in favor of BCP 4). Minor versions and patches would become less frequent as fewer and fewer people were interested in it and fewer parishes were using it, and eventually support would sunset.

