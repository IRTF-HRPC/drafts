	--- 
title: Meeting asynchronously with mailing lists
abbrev: async
docname: draft-knodel-async-01
category: info

ipr: trust200902
area: general
workgroup: shmoo
keyword: Internet-Draft
stand_alone: yes
pi:
  rfcedstyle: yes
  toc: yes
  tocindent: yes
  sortrefs: yes
  symrefs: yes
  strict: yes
  comments: yes
  inline: yes
  text-list-symbols: -o*+

author:

-
       ins: M. Knodel
       name: Mallory Knodel
       organization: CDT
       email: mknodel@cdt.org

-
       ins: K. Novotný
       name: Karel Novotný
       organization: Association for Progressive Communications
       email: karel@apc.org

normative:

informative: 
   BCP25:
   RFC7776:

   Title: Silence
     title: "Silence procedure"
     date: 2020
     author:
        - ins: Wikipedia
        - ins: 
     target: https://simple.wikipedia.org/wiki/Silence_procedure

   Title: APC
     title: "Closer than ever: A guide for social change organisations who want to work online"
     date: 2011, 2020
     author:
        - ins: Association for Progressive Communications
        - ins: 
     target: https://www.apc.org/en/node/36145/#tools

--- abstract

For when we can't meet in person, when there's interim work to be done, or just because the task calls for it, an asynchronous text-based meeting can sometimes be perfectly productive and useful. Given how much the IETF uses email already [rfc3934] this document aims to create additional guidance for co-chairs and meeting facilitators who might want to host a meeting asynchronously with mailing lists. Drawing from decades of facilitation experience in global networks, the document also treats unique considerations for facilitators that are introduced by this meeting methodology.

--- middle

# Introduction: Why?

Meeting online introduces new and novel challenges to in-person meetings. Getting people online in a synchronous meeting is generally difficult and demanding on everyone. High costs include logistics and  The difficulty grows exponentially with the number and diversity of desired participants. If the meeting participants cut accross different timezones, participation to such a meeting requires a real committment and sacrifice from many participants. Although the synchronous voice/video meetings imitate face-to-face meetings, they fall short in terms of productivity in serious ways. Particularly when meetings are large, synchronous discussion at scale is usually questionable, and the real outputs rarely justify the investment needed from everyone in orser to participate.

By contrast, well-structured asynchronous meetings have pacing and mixed-methods that gives participants an opportunity to participate in the ways which work for them, and when they can. Especially during a global crisis, but really whenever one is expected to participate in remote work, asynchronous meetings are more compatible with individuals' limitations because they can adapt their participation to their realities - removing the liklihood of time clashes, which are seemingly ever present in synchronous meetings.

Since email is ubiquitous, mailing list software can be the centerpiece of an asynchronous meeting toolchain. This is particularly smooth for IETF participants given the established and discplined use of mailing lists for IETF work. Throughout the 2020 pandemic arrangements for virtual IETF meetings there has been a noticable persistence in "taking it to the list" when co-chairs seek to build consensus, even though in theory there are a reduced number of barriers for an engaged IETF participant to join an online meeting. This indicates that even during synchronous, online IETF meeting activity on mailing lists is still important.

# How

This document outlines how to, over a time-bound period, cultivate productive mailing list activity, in order to rely less on synchronous moments, or not at all.

## Before: Meeting preparation

Preparation for any meeting is key. However there are particular opportunities with an asynchronous meeting in which chairs can take extra care to ensure productivity for the group, but also efficiency for their work as facilitators during the meeting itself.

First, set up an organising space. Perhaps the datatracker is enough for IETF meetings, but with the addition of a wiki space, or creative use of Meeting Materials. Participants will be switching their attention radars on and off in different moments -- that's the point! But they won't be present when you ask them to, or when you email key information. The ongoing flow of participants and presenters asking for clarifying details need to be gently directed to one place with all of the meeting instructions and resources to all these details somewhere visible (header or footer of all messages during the meeting, etc).

Next, determine distinct discussion topics. It will not be enough to have each presenter or document author write to the mailing list to start a discussion about their work. Chairs will need to create a structured agenda, with threads for each topic (see next section) opened with a clear message detailing the topic's purpose, objective and process. This implies that "agenda review" needs to happen well in advance of the beginning of the asynchronous meeting.

For each topic it is critical to agree ahead of time on this topic-opening message, ideally with the presenter(s) and author(s). The message should contain enough background and context such that all participants start with clarity on prior discussion, recent decisions, and most importantly the "POP" of the thread, or asynchronous discussion, itself. What is the purpose of getting everyone's focussed attention on this threaded discussion for the next few days? What's the objective-- perhaps a set of decisions-- for the chairs, and possibly the author(s)? Each thread needs its own process, too, explained-- eg watch the presentation, read the draft, compare versions, look at the open issues, take a poll, etc. Make sure materials are managed: drafts should be listed on the meeting materials page, presentations uploaded, and if other videos or resources are needed that they are clearly linked from the same place.

Plan to give participants a social outlet during the meeting. Advanced planning could help the chairs facilitate moments throughout the meeting that happen spontaneously in an in-person meeting, and even sometimes in online conferencing. The chitchat about current events, our private lives, or something everyone cares about. Creating space for this on an agreed agenda will set the expectation for participants that the meeting will be interesting and include moments of humanity and levity.

## During: Facilitating and participating

### Welcome

An opening welcome message is very important and should be the first thread opened. It should list the purpose and objective of the welcome message, which is to start the meeting and ensure everyone knows the agenda and how to participate. It's the place where compliance, bluesheets and other information is shared for the first time. The details outlined in the welcome message should be available in the meeting space as the agenda, or reference materials, for easy reference.

It's recommended that basic instructions to participants include being present some fixed number of hours for the duration of the meeting, eg plan to set aisde 10-15 minutes per day for a week to engage in this meeting.

### Mixed methods

An agenda item might require a mixed method, for example a presentation about a draft delivered by the draft's author. In each topic thread, the process should be clear for all participants, eg watch the presentation and reply to the topic thread with questions (like a mic line). It may well be that a synchronous moment is needed, over voice, video conference, jabber, etc. For these moments, and for the benefit of meeting participants unable to attend, both record the session and create notes immediately and use them as the basis for the continuation of the thread. Mixed method can be powerful, but hard to get right. You don't want to keep participants unable to participate synchronously waiting 2-3 days for a readout on what happened.

### Polling and reaching consensus

The first step to reaching a destination is knowing where you're going. Facilitators and chairs will have an easier time building consensus from the list if from the beginning it's clear what is being built. Perhaps employing silence procedure is wise given list subscription sizes.[Silence]

There may be innovations beyond a simple polling tool to substitute humming that others in the shmoo WG may be keen to adopt and that would be appropriate in an asynchronous space.

### Threading and subject lines

As mentioned in the above section on meeting preparation, allocating each agenda item to a topic thread allows the facilitator to open distinct discussions on the mailing list with clarity of purpose, objective and process. A clear subject line should be used for each threaded topic. Forking discussion topic threads by pre-pending can be a useful way to identify sub-topic areas, but chairs might consider whether they would like to be in control of those changes or allow spontaneous forking by any participant during the time-bound meeting.

It is generally assumed that the mailing list be used only for the meeting during the meeting dates, eg no other threads should be opened without checking with the chair. Likewise, when the meeting has ended, that no one should reply to, eg continue discussion of, meeting topic threads.

### Social/AOB

Chairs can facilitate social exchange during the meeting, emmulating the in-person experience to some small degree. That includes allocating separately a welcome and agenda message, so that the welcome message can give participants a chance to "check in" on others, offer up personal annecdotes, or share links. There may be a current event that has its own topic thread, but is only tangentially related to the meeting that would compell meeting participants to check in on the meeting.

Any other business is often part of an IETF WG/RG meeting agenda, and creating a topic thread can allow for asynchronous proposals for other topics to discuss from participants themselves, though as mentioned in the meeting preparation section above, agenda review should ideally be done well in advance of the first day of the meeting.

## After: The destination

After the closing message ends the meeting, it's a useful and helpful thing to take a few extra steps to ensure all objectives of the meeting were achieved, that leaders and authors are clear on their next steps, and that participants know they shouldn't reply to meeting threads anymore.

### Closing threads

While notetaking isn't really necessary, since the list archive itself is a verbatim account of the meeting, having a summary of each thread will be useful. Especially since each thread should already have outlined a clear purpose and objective, the summary should easily address whether or not those were fulfilled.

Participants should be given a chance to correct the closing thread summary for inaccuracies only.

### Meeting reports

A meeting report might be a compendium of all closing threads, and constitute the official notes for the meeting that appear in the data tracker. It might also helpfully include statistics on participation.

### Meeting feedback

In all cases, but especially with new methodologies like MAML, it's recommended to conduct a short post-meeting evaluation with all participants that can help facilitators determine what worked, what didn't and to collect any other meta views that participants might want to share. Rather than an open thread, meeting evaluations are best conducted with anonymous surveys.

# Considerations

## Defining participation

There are yet unexplored models for how to host a full IETF meeting held only on mailing lists given subscription to lists isn't monetised. It isn't recommended to hold an asynchronous meeting over several days, and encompassing an IETF virtual synchronous moment for which participants would need to pay, as this would put list-only participants at a disadvantage.

Another consideration is how to handle bluesheets for an asynchronous meeting held on a mailing list with hundreds of subscribers. For those not reading the list carefully, they may be surprised to know that their commentary on a mailing list thread consistutes official participation in an IETF meeting. Likewise it would be difficult to ask participants to sign in when attention will be rather fluid.

## Translation and accessibility

Text-based communications present opportunities for increased accessibility of discussions because they can be fed into machine translators and screen readers; read, reread and referenced more easily. Asynchronicity removes time-related constraints sometimes present in accessibility tools.

## Netiquette and participant instructions

While most IETFers are well versed in proper mailing list netiquette, perhaps reminders of how the chairs would prefer the meeting flow in its discussion could be useful.

## Compliance

Lastly delivery of the Note Well and other compliance considerations when meeting only on a mailing list need to be explored further.

At all times, but especially when faced with potentially a huge increase in list traffic, chairs should be ready to enforce the IETF Code of Conduct [RFC7776].

# Annexes and examples

## Guidance from "Closer Than Ever"

The Association for Progressive Communications was founded in 1990 and has used mailing lists in creative ways to connect its global network. Their publication on working remotely was rebooted in 2020 and here's a relevant excerpt [APC]:

When the email lists are used for meetings, we always establish a clear procedure so that everyone involved in the meeting knows how long we will be discussing the topics addressed, what topics will be discussed each day or each week, and how subject lines will be handled.

A typical online meeting can take place over three weeks:
	* Week 1: signing in and posting of discussion topics
	* Week 2: discussion of topics
	* Week 3: voting.

These are the basic steps that we follow for our online council meetings:

	1. Two weeks prior to the meeting, the meeting facilitators will post the proposed meeting agenda and motions to the Board of Directors for approval.    
	2. One week prior to the meeting, the executive director will post the meeting agenda, including the full slate of proposed motions, to the council email list.
	3. Then we start the discussion by sending out one message for each point of the agenda, so that members may reply accordingly to each subject line. The first messages are for checking in: each member that will participate in the meeting sends a short message stating their name and organisation, so that we all know who is participating. Then we continue by replying to messages according to the subject headings of the agenda.
	4. Once the meeting is finished there is an official message closing the meeting and thanking everyone for their participation. All council members will then receive a summary of the points discussed and the agreements reached.
	5. During the meeting the facilitator has a key role in making sure everyone is participating, clarifying any doubts in the procedures, and asking relevant questions to those members who have been silent (sometimes off list, encouraging them to participate).

## Sample welcome message and agenda

Subject: shmoo-IETF109 0: Agenda and process overview

This message is to open the [shmoo Meeting at IETF 109]. The meeting will take place on this list between [DD-DD Month YYYY].

The process for the meeting is the following:

The chairs will open specific topic threads by sending opening messages to this list. 

Reply to any thread at any time, just make sure to keep the subject line intact so it is clear on what topic you are responding.

Below is the agenda. Please use this topic thread only if you have something to say about the agenda or the process.

Remember that all relevant information and all documents shared in this meeting are available on the datatracker: [URL]

Please shout with any questions.

Welcome to the meeting! :)

------------------------------------------------------------------------------
      Stay Home Meet Only Online IETF 109 Meeting, [DD-DD Month YYYY]
      AGENDA
------------------------------------------------------------------------------
* shmoo-IETF109 0: Agenda and process overview (this thread) 
* shmoo-IETF109 1: Check in and social space
* shmoo-IETF109 2: draft-shmoo-firstexample-00
* shmoo-IETF109 3: draft-shmoo-secondexample-07
* shmoo-IETF109 4: draft-thirdexample-03
* shmoo-IETF109 5: Any other matters
* shmoo-IETF109 6: Closing the meeting

