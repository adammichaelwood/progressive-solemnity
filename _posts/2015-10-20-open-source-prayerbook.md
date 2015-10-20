---
layout: essay
title: Open Source Prayerbook
summary: "The only way to ensure that the voices of all are respected in the final product of BCP revision is by making sure that all of these voices are present and respected in the process of revision."
---

So far, most of the conversation about Prayerbook Revision has been focused on content. It seems that the people who have pushed for the coming revision have done so out of a concern for "updated" content (whatever that means), and most of the public conversations have been concerned with content --- language, rubrics.

This makes perfect sense. The content of the prayerbook is the closest thing we have to an official statement of theology. The words of the prayers, the order of worship, and the rubrical instructions guide our weekly or daily rhythms of prayer and form the foundations of our personal and communal spirituality.

But talk of content, I think, is premature at this stage. The passionate cries for moderation coming from some, and for greater liberalization coming from others, will have been forgotten three, six, or nine years from now. What is needed is a _process_ by which these voices --- all voices --- can have a real voice in the ongoing work of revision.

The [resolution that was passed at the 2015 General Convention](http://www.generalconvention.org/gc/2015-resolutions/A169/current_english_text) directed SCLM to "__prepare a plan__ for the comprehensive revision" of the BCP.

If you care about the content of the next Book of Common Prayer --- and you should --- you should care about what this plan looks like.

Here is what I propose.

## Open Source the Prayer Book

The next Book of Common Prayer should be an Open Source Prayer Book.

This cannot be work undertaken by a small committee of academics and insiders, by those with power in the institutional church, far away from the real lives of regular worshipers. 

And --- just as crucially --- it cannot seem to be that way either.

No matter how many draft revisions or proposed texts are released, no matter how many times the SCLM calls for trial use and feedback, if the process for revision is not radically open and transparent, there will very likely be a strong sense that a new prayer book is being imposed on the church against the will of a large portion of the faithful. 

The recent strong reaction against what [people _thought they heard_ in Ruth Meyers's recent statements about Prayer Book revision](http://livingchurch.org/greener-prayer-book) are indicative of underlying fears about the content of the next Book of Common Prayer  --- the fear that beloved prayers will be taken away, that traditional images will be banned, that ancient statements of belief will be forgotten, that sacred metaphors will be thrown out. Underlying all these fears, I believe, is a fear of voicelessness.

The Prayer Book gives voice to our faith. 

There are some for whom that voice is inadequate, a voice not their own. They --- quite rightly --- long for a new Prayer Book, for new language that will give words for their mouths which can match the meditations of their hearts.

Others are fearful that their voice in prayer will be taken away, that they will be required to use new and unfamiliar words, that the truth as they understand it will be abandoned.

In the discussion about BCP revision at General Convention, the Rev. Canon John Floberg, deputy from North Dakota, warned that "among the Lakota-Dakota people of the Plains, it takes on average 40 years to substantially translate the prayer book once it’s revised." I would say that it takes at least that long --- a Biblical generation --- for new prayer language to become the native prayer language of a worshiping community. 

The only way to ensure that the voices of all are respected in the final product of BCP revision is by making sure that all of these voices are present and respected in the process of revision.

And the only way to do that is to make the process Open Source.

## What does Open Source mean?

Open Source is a methodology which has developed over the last several decades in software development. It emphasizes freedom over control, community over hierarchy, diversity over uniformity, collaboration over competition, and permission over restriction.

Practically speaking, to Open Source the next Book of Common Prayer would mean applying Open Source principles in the following, highly interrelated areas:

### Open Source Process

In a typical Open Source development process, anyone can contribute in a wide variety of ways. For software development this primarily means writing code, but not exclusively that. It also means creating documentation, tutorials, and tests. It means fixing bugs as well as creating new features. It means participating in discussions. It means trying out new versions before they are formally released to the public.

To open the process of Prayer Book revision means allowing anyone to contribute in a wide variety of ways. Contributing to the texts of prayers and rubrics, participating in discussions, providing research, proofreading, trying things out.

Now... At this point, most people without Open Source experience start panicking. This seems like chaos. How do you control all of this?

Open Source is free for all, but it is not a free-for-all. Every Open Source project in existence has a relatively small group of core contributors that provide leadership and guidance, and -- ultimately -- decide what "makes the cut" and what doesn't. Only a few typically have "commit privileges."

The difference is that you have a small group of people shepherding a large community of contributors, rather than a small group of people doing all the work and making all the decisions in private. In that way, Open Source development mirrors best practices in congregational leadership, rather than the outdated model wherein the pastor and a small group of insiders make all the decision and do all the work on behalf of a congregation of consumers of religion.

### Open Source Technology

In order for an Open Source process to work, it must be conducted on a technical platform designed to support that process. Prayerbook revision cannot be conducted via emailed Microsoft Word documents.

The most obvious choice for such a platform is git and [Github](http://github.com).

Git is a version control system. It makes it (relatively) easy for many different people to work on the same project at the same time, and merge their work as needed. It tracks changes and edits, allows multiple versions to exist side by side, and radically democratizes the process of collaboration.

Github provides a central hub for git-powered projects, making them publicly accessible (even to people who don't use git), and provides a number of collaboration tools such as discussion forums, bug trackers, project wikis for documentation, and other important features.

This platform accomplishes the goal of making the process radically transparent. Every decision, every revision, every discussion, has a URL that can be linked to, a date stamp, and the name of the person responsible for accepting the commit. 

### Open Format

One of the most fundamental characteristics of Open Source software --- the quality that gives it its name --- is that the source code is open. That is to say --- available, accessible, viewable, editable.

Closed source applications are provided in compiled, executable binary form. If you were to open the file up in a code editor, you'd see a bunch of gibberish numbers. The human-written source code has been compiled into a form usable by the computer, but impenetrable to humans.

When we publish books, or even PDF documents and online liturgical resources, they are usually provided in a "compiled" form. The page numbers, the fonts, the margins, the styles --- all of it, not just the essential text --- is embedded into the file.

Have you have ever tried copy-pasting Psalms or prayers out of the [Online BCP](http://www.bcponline.org/) for use in a program? How much time do you waste stripping out the page numbers, the weird formatting, and other remnants of page layout? (I do this on a regular basis, and have developed several automated tools and techniques for it, and it is _still_ a pain.)

If the source material for the next BCP is made available _as source material_ --- that is to say, minimally formated plain text (using something like [Markdown](https://en.wikipedia.org/wiki/Markdown)), then it would be infinitely easier for people to remix and reuse as needed.

And it can still be provided in an easy-to-use, consumable, "compiled" format. These are not mutually exclusive goods. This very blog post, for example, is available in a "compiled" format --- with styling and typographical design --- on the page you are currently reading. But you can also access the [plain-text source code](https://github.com/adammichaelwood/progressive-solemnity). Many, many tools are available ([kramdown](http://kramdown.gettalong.org/) and [Pandoc](http://pandoc.org/), just for examples), and [new ones could be created](http://pybuilder.github.io/), which would automatically compile lightly-formatted plain text source code into ready-to-publish books in a variety of formats. (This would also make it _much easier_ to produce online versions, app versions, large-print versions, abridged versions, and translations).

### Open Licensing

I am extremely sympathetic to the idea that [the next Prayer Book should be _a book_](http://jessezink.com/2015/10/12/a-single-wish-for-a-new-book-of-common-prayer/), but I also think it is clear that the present and likely future of liturgical worship in our church involves remix, reuse, and republishing of Prayer Book material. While a single, usable pew-book should be the standard form of the liturgical text, we need to make it as easy as possible for congregations and worshiping communities (as well schools, institutes, publishing houses, and entrepreneurs) to rearrange and repackage the material in the BCP in a manner that will fit their needs.

Open formatting, discussed above, is a huge part of that. But so is Open Licensing. There should be no artificial legal hurdles to the use of Prayer Book materials by the church. 

I highly commend the use of Open Source licensing such as [Creative Commons](http://creativecommons.org/) for all materials created by the institutional church.

This in no way creates barriers to the inclusion of copyright texts and other work (such as music that might be included in a hymnal) --- mixed license works are published all the time, just as the current hymnal contains both copyrighted and Public Domain works. If there is a strong desire to hold a [monopoly](https://en.wikipedia.org/wiki/Simony) over the publication of the complete, official Book of Common Prayer, that can also be accommodated within a framework that clearly places the contents into the Commons.


## The Future must be Open

Episcopalians talk a good game about being progressive and democratic. We like words like "transparent" and "collaborative." We say we believe in empowering people, and communities.

If we mean any of those things, if we are to have any integrity at all, we cannot be a church that allows a handful of well-connected insiders to set the liturgical agenda of the entire church.

If the liturgy is to become the work of the entire people of God, then the liturgical books must be --- as widely as possible --- the work, the ongoing work --- of the entire church. If the law of prayer is the law of our belief, then the process by which we revise our prayer must reflect our beliefs about who we are, and what kind of church we are. If the next Book of Common Prayer is really going to be _Common_ Prayer, then the common people must have a voice in its composition, and the final product must belong to the Commons.

## Further Reading

 - If you are still trying to wrap your head around how a large institution like the Episcopal Church can benefit from Open Source methodology, I highly commend [The Open Organization](http://amzn.to/1GnROlz) by Jim Whitehurst, CEO of Red Hat.

 - [Ben Balter](http://ben.balter.com/) is an Open Source evangelist, promoting the use of Open Source technology and methodology in governments. Many of the institutional hurdles faced by government adoption of Open Source have parallels in the church.

 - [David Wiley](http://opencontent.org/blog/) blogs about Open Content. The BCP is not a software program, and not every aspect of Open Source development applies. Open Source Content has its own set of particular issues which need to be addressed, and David does a good job of exploring these. Most of his work involves schools and universities, which have a lot of parallels to churches.

 - [The Cathedral and the Bazaar](http://amzn.to/1RUirzM) by Eric S. Raymond is a classic book on the benefits of Open Source methodology.

 - [This blog](http://progressivesolemnity.org). Please subscribe (see the form up in the sidebar, or the [RSS Feed](http://progressivesolemnity.org/feed.xml)). I plan to spend a lot of time over the next few years promoting the use of Open Source methodology in the process for revising the Prayer Book.