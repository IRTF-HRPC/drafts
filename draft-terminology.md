---
title: Terminology, Power, and Inclusive Language in Internet-Drafts and RFCs
abbrev: Terminology
docname: draft-knodel-terminology-03
date: 2020-06-16
category: bcp

ipr: trust200902
area: IETF
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
       organization: Center for Democracy & Technology
       email: mknodel@cdt.org

-
       ins: N. ten Oever
       name: Niels ten Oever
       organization: Texas A&M University and University of Amsterdam
       email: mail@nielstenoever.net

normative:

   RFC2119:
   RFC8174:

informative:

   RFC7322:
   RFC8499:
   RFC8782:
   RFC8783:
   RFC8612:

   Burgest:
      title: “Racism in Everyday Speech and Social Work Jargon.”
      author:
         - ins: David R. Burgest
      date: 1973
      seriesinfo: "Social Work, vol. 18, no. 4, 1973, pp. 20–25"
      target: www.jstor.org/stable/23711113.

   Eglash:
      title: "Broken Metaphor: The Master-Slave Analogy in Technical Literature."
      author:
         - ins: Ron Eglash
      date: 2007
      seriesinfo: "Technology and Culture, vol. 48 no. 2, 2007, pp. 360-369."
      target: https://doi.org/10.1353/tech.2007.0066

   BrodieGravesGraves:
      title: "Masters, slaves, and infant mortality: Language challenges for technical editing"
      author:
         - ins: Heather Brodie Graves
         - ins: Roger Graves
      date: 1998
      seriesinfo: "Technical Communication Quarterly, 7:4, 389-414"
      target: https://doi.org/10.1080/10572259809364639

   Wyatt:
       title: "Danger! Metaphors at Work in Economics, Geophysiology, and the Internet"
       author:
          - ins: Sally Wyatt
       date: 2004
       seriesinfo: "Science, Technology, and Human Values, Volume: 29 issue: 2, page(s): 242-261"

   Lakoff:
       title: Metaphors We Live By
       author:
          - ins: George Lakoff
          - ins: Mark Johnson
       seriesinfo: U of Chicago P, 1980.

   Orwell:
      title: Politics and the English Language
      author:
         - ins: George Orwell
      date: 1946

   McClelland:
      title: We need better metaphors
      author:
         - ins: J. McClelland
      date: 2011
      target: https://current.workingdirectory.net/posts/2011/master-slave

   UDHR:
     title: The Universal Declaration of Human Rights
     date: 1948
     author:
        - org: United Nations General Assembly
     target: http://www.un.org/en/documents/udhr/

   Fanon:
     title: Black skin, white masks
     date: 1952
     author:
        - ins: F. Fanon

   Jansens:
      title: "I don't believe in PC"
      date: 2008
      author:
         - ins: Bart Jansens
      target: https://www.drupal.org/project/project_issue_file_review/issues/343414#comment-1164514
     
   Python:
      title: "'master-slave' Terminology Was Removed from Python Programming Language"
      date: 2018
      author:
         - ins: Daniel Oberhaus
      target: https://motherboard.vice.com/en_us/article/8x7akv/masterslave-terminology-was-removed-from-python-programming-language

   Django:
      title: "#22667 replaced occurrences of master-slave terminology with leader/follower #2692"
      date: 2014
      author:
         - ins: fcurella
      target: https://github.com/django/django/pull/2692

   Django2:
      title: "comment on #22667 replaced occurrences of master-slave terminology with leader/follower #2692"
      date: 2014
      author:
         - ins: lynncyrin
      target: https://github.com/django/django/pull/2692#issuecomment-44221563

   Wikipedia:
      title: Slavery in the 21st century
      date: 2018
      author:
         - org: Wikipedia
      target: https://en.wikipedia.org/wiki/Talk:Slavery_in_the_21st_century

   Drupal:
      title: "Replace 'master-slave' terminology with 'primary/replica'"
      date: 2014
      author:
         - ins: Xano
      target: https://www.drupal.org/project/drupal/issues/2275877

   Grewal:
      title: "The 'Bad Is Black' Effect"
      date: 2017
      author:
         - ins: D. Grewal
      target: https://www.scientificamerican.com/article/the-bad-is-black-effect/

   socketwench:
      title: "Even in tech, words matter"
      date: 2018
      author:
         - ins: socketwench
      target: https://deninet.com/blog/2018/09/09/even-tech-words-matter
      
   ISC:
      title: "@ISCdotORG reply tweet"
      date: 2017
      author:
         - ins: Internet Systems Consortium
      target: https://twitter.com/ISCdotORG/status/943152507211071489
      
   Github:
       title: "Github to Remove 'Master/Slave' Terminology From its Platform"
       date: June 2020
       author:
         - ins: Kevin Truong 
         - org: VICE
       target: https://www.vice.com/en_us/article/k7qbyv/github-to-remove-masterslave-terminology-from-its-platform

--- abstract

This document argues for moving away from certain specific language conventions sometimes used by RFC authors and the RFC Production Centre in order to encourage the use of more inclusive terminology in Internet-Drafts that are work in progress, and in new RFCs that may be published in any of the RFC series. The document also provides examples of inclusive terminology as precise alternatives for these conventions.

--- middle

# Introduction

According to {{RFC7322}}, "The ultimate goal of the RFC publication process is to produce documents that are readable, clear, consistent, and reasonably uniform," and one function of the RFC Editor is to "[c]orrect larger content/clarity issues; flag any unclear passages for author review." Documents that are published as RFCs are first worked on as Internet-Drafts.
 
Given the importance of communication between people developing RFCs, Internet-Drafts (I-D's), and related documents, it is worth considering the effects of terminology that has been identified as exclusionary. This document argues that certain obviously exclusionary terms should be avoided and replaced with alternatives. We propose nothing more than additional care in the choice of language just as care is taken in defining standards and protocols themselves.
 
This document presents arguments for why exclusionary terms should be avoided in Internet-Drafts and RFCs, describes the problems introduced by some specific terms, and proposes alternative language. The terms discussed in this document include "master-slave" and "whitelist-blacklist". There is a final section on additional considerations and general action points to address future RFCs and I-D's. Lastly, a summary of recommendations is presented.

# Terminology

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "NOT RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in BCP 14 {{RFC2119}}{{RFC8174}} when, and only when, they appear in all capitals, as shown here.

# Terminology and Power in Internet-Drafts and RFCs

According to the work of scholar Heather Brodie Graves from 1993, "one goal of the application of rhetorical theory in the technical communication classroom is to assess the appropriateness of particular terms and to evaluate whether these terms will facilitate or hinder the readers’ understanding of the technical material" {{BrodieGravesGraves}}. This implies that in order to effectively communicate the content of I-Ds and RFCs to all readers, it is important for Authors to consider the kinds of terms or language conventions that may inadvertently get in the way of effective communication. She continues, "complex and subtle configurations of sexist, racist, or ethnocentric language use in technical documents can derail or interfere with readers’ ability and desire to comprehend and follow important information."

Indeed, problems of language are problems of everyday speech. Racist and sexist language is rampant and similarly counter-productive in other sectors, notably social work {{Burgest}}. The terms "master-slave," treated in detail below are present in other realms of technology, notably "automotive clutch and brake systems, clocks, flip-flop circuits, computer drives, and radio transmitters" {{Eglash}}.

However as noted in the research by Ron Eglash, this seemingly entrenched technical terminology is relatively recent. It is not too late for these terms to be replaced with alternative metaphors that are more accurate, clearer, less distracting, and that do not offend their readers. Language matters and metaphors matter. Indeed, metaphors can be incredibly useful devices to make more human the complex technical concepts presented in RFCs. Metaphors should not be avoided, but rather taken seriously. Renowned linguist George Lakoff argued in 1980 that the ubiquitous use of metaphors in our everyday speech indicates a fundamental instinct to "structure our most basic understandings of experience" {{Lakoff}}. Metaphors structure relationships, and they frame possibilities and impossibilities {{Wyatt}}.

Like Graves, this document recognises the monumental challenge of addressing linguistics and power, and attempts to "promote awareness that may lead to eventual wide-spread change" {{BrodieGravesGraves}} and suggests first steps for actions that may remedy the inadvertent use of undesirable terms'. To that end, the list below is a tersely written set of IETF-specific arguments as to why the RFC Editor should be encouraged to correct other content and clarity issues with respect to excluding language and metaphors:

 * The RFC series is intended to remain online in perpetuity. Societal attitudes to offensive and excluding language shift over time in the direction of more empathy, not less.
 * That excluding terms in RFCs are largely hidden from the larger public, or read only by engineers, is no excuse to ignore social-level reactions to the terms. If the terms would be a poor choice for 
user-facing application features, the terms should be avoided in technical documentation and specifications, too.
 * At the time of this drafting, the digital technology community has a problem with monoculture. And because the diversity of the technical community is already a problem, a key strategy to breaking 
monoculture is to ensure that technical documentation is addressed to a wide audience and multiplicity of readers.
 * And yet the technical community already includes members who take offense to these terms. Eradicating the use of excluding terminology in official RFCs recognises the presence of and acknowledges the 
requests from black and brown engineers and from women and gender-non-conforming engineers to avoid the use of exclusive terminology.

This document does not try to prescribe terminology shifts for any and all language that could be deemed exclusive. Instead what follow are specific alternative suggestions to "master-slave" and "white-blacklist" and the rationale for the use of the alternatives. Additional considerations are presented in a subsequent section.

## Master-Slave

Master-slave is an offensive and exclusive metaphor that will and should never become fully detached from history. Aside from being unprofessional and exclusive it stifled the participation of students whom Eglash interviewed for his research. He asks: "If the master-slave metaphor affected these tough-minded engineers who had the gumption to make it through a technical career back in the days when they may have been the only black persons in their classes, what impact might it have on black students who are debating whether or not to enter science and technology careers at all?" {{Eglash}}

Aside from the arguably most important reason outlined above, these terms are becoming less used and therefore increasingly less compatible as more communities move away from its use (eg {{Python}}, {{Drupal}}, {{Github}} and {{Django}}. The usage of 'master' and 'slave' in hardware and software has been halted by the Los Angeles County Office of Affirmative Action, the Django community, the Python community and several other programming languages. This was done because the language is offensive and hurts people in the community {{Django2}}. Root operator Internet Systems Consortium stopped using the terms because they were asked to {{ISC}}.

In addition to being inappropriate and arcane, the master-slave metaphor is both technically and historically inaccurate. For instance, in DNS the 'slave' is able to refuse zone transfers on the ground that it is malformed. The metaphor is incorrect historically given the most recent centuries during which "the role of the master was to abdicate and the role of the slave was to revolt" {{McClelland}}. Yet in another sense slavery is also not 'just an historic term', whereas freedom from slavery is a human-rights issue {{UDHR}}, it continues to exist in the present {{Wikipedia}}. Furthermore, this term set wasn't revived until recently, after WWII, and after many of the technologies that adopted it were already in use with different terminology {{Eglash}}.

Lastly, we present not an additional rationale against their use, but an indicator of actual racism in the community that has been surfaced as a result of this larger debate among technologists, "I don't believe in PC (political correctness), mostly because the minorities constantly use it to get away with anything" {{Jansens}}. This illustrates the need to, as Graves is cited above as saying, continue to raise awareness within our community for eventual, lasting change on the continued front of struggle against the racists amongst us.

### Suggested Alternatives

There are also many other relationships that can be used as metaphors, Eglash's research calls into question the accuracy of the master-slave metaphor. Fortunately, there are ample alternatives for the master-slave relationship. Several options are suggested here and should be chosen based on the pairing that is most clear in context:

 * Primary-secondary
 * Primary-replica
 * Active-standby
 * Writer-reader

Since the use of master-slave is becoming less common in other technical communities, it is best to simply duplicate the metaphor being used by comparable or interoperable technologies. The IETF can show positive leadership in the technical community by setting standards without using offensive and exclusive metaphors.

For the DNS, RFC 8499 defines the current best practise for DNS terminology and uses the term pair 'primary' and 'secondary' {{RFC8499}}.

## Blacklist-Whitelist

The metaphorical use of white-black to connote good-evil is exclusive. While master-slave might seem like a more egregious example of racism, white-black is arguably worse because it is more pervasive and therefore more insidious. While recent headlines have decried the technical community's use of master-slave, there is far less discussion about white-black despite its importance. There is even a name for this pervasive language pitfall: the association of white with good and black with evil is known as the "bad is black effect" {{Grewal}}.

Indeed, there is an entire book on the subject, written by renowned authority on race, Frantz Fanon. In his book "Black Skin, White Masks," Fanon makes several persuasive arguments that standard language encodes subconscious in-group, out-group preferences {{Fanon}}.

In the case of blacklist-whitelist in the technical documentation of I-Ds and RFCs, it is entirely a term of art and an arbitrary metaphorical construct with no technical merit. There are scientific uses of black that are related to light-- black holes are black because light cannot escape them. Blacklist-whitelist is not a metaphor for lightness or darkness, it is a good-evil metaphor and therefore this trope has significant impact on how people are seen and treated. As we've seen with metaphors, its use is pervasive and, though not necessarily conscious, perceptions do get promulgated through culture and repetition.

As with master-slave, we save our technical argument for last, referencing and presenting first the reasons for the use of non-offensive, alternative terminology for the sake of our humanity. Indeed, our technical argument is incredibly succinct: Why use a metaphor when a direct description is both succinct and clear? There can be absolutely no ambiguity if one uses the terms, as suggested below, allow-block rather than white-black.

### Suggested Alternatives

There are alternatives to this terminology set that vastly improve clarity because they are not even metaphors without adding a single additional character. The alternatives proposed here say exactly what they mean. Examples of specifications that use these alternative terms are also provided for illustration purposes.

 * Accept-list and Drop-list (see for examle {{RFC8612}}, {{RFC8782}}, and {{RFC8783}})
 * Blocklist-allowlist
 * Deny-allow
 * Droplist-accesslist
 * Drop-permit
 * Block-permit

## Other Considerations

As described in the preceding sections, the language used in technical documentation, like all written text, creates and reinforces expectations and stereotypes. We propose nothing more than additional care in the choice of language just as care is taken in defining standards and protocols themselves. The two examples provided above are not the only cases of offensive language to be avoided, and many more can be collected. However, these two examples are particularly significant and require immediate action. We use this section to broaden the context of other offensive and excludig terminologies to encompass additional concerns.

There are many other metaphors present in technical documentation that are "terms of art" but that have no technical basis whatsoever. 

If any of  these metaphors is offensive there is no excuse for its continued use. A term like "man-in-the-middle" is not technically useful. It is not a standard term, not as clear as its alternative "on-path attacker", and should therefore be avoided. When presented with the opportunity to employ the use of metaphors or to unthinkingly repeat terms of art that connote gender or race, Authors should simply find a better way to explain themselves. A fun read on the politics of colloquial speech by George Orwell should dissuade any clever Author from using tired explanatory metaphors {{Orwell}}.

Up until recently, strict English grammatists like Orwell decried the use of the neutral pronoun "they". Without a neutral singular pronoun, "he" is assumed as the default singular pronoun when the gender of the person is unknown or ambiguous. However, that has changed, and it is now widely accepted that "they" can be used as a neutral singular pronoun. Since it is unlikely that all implementers and infrastructure operators are of any particular gender, "he" should never be used to refer to a person in I-Ds and RFCs. An Author who uses male examples sets male-ness as a standard.

Militarised metaphors are also a pervasive problem in language, perhaps even more so in technical communities because of the historical and actual relationship between technology and war. We welcome additional examples of terminology that might be avoided through more awareness and thoughtfulness.

# Summary of Recommendations

To summarise, we have bulleted some very concrete action points that can be taken by Editors, reviewers and Authors, both present and future as they develop and publish Internet-Drafts and new RFCs.

Authors SHOULD:
 * Replace the excluding term "master-slave" with more accurate alternatives, for instance from the list of <xref target="master-slave"/>.
 * Replace the excluding term "blacklist-whitelist" with more accurate alternative, for instance from the list of suggested alternatives at <xref target="blacklist-whitelist"/>.
 * Reflect on their use of metaphors generally
 * Use the neutral "they" as the singular pronoun, and
 * Consider changing existing exclusive language in current (reference) implementations {{socketwench}}
 * Consult the style sheet maintained by the RFC editor.

RFC Editor MUST:
 * Offer alternatives for excluding terminology as an important act of correcting larger editorial issues and clarifying technical concepts and
 * Maintain a style sheet that collects all terms that have been considered and indicate wheter they are deemed acceptable, and if not what terms Authors should consider instead 
 * Suggest to Authors that even when referencing other specifications that have not replaced offensive terminology, the Authors could use another term in their document and include a note to say that they have used the new term as a replacement for the term used in the referenced document.

# Further reading

'‘Anyone can edit’, not everyone does: Wikipedia and the gender gap' by Ford, Heather and Wajcman, Judy (2017) Social Studies of Science. ISSN 0306-3127

Grant, Barbara M. "Master—slave dialogues in humanities supervision...https://doi.org/10.1177/1474022207084880

Miller, Carolyn. "A Humanistic Rationale for Technical Writing"

# Security Considerations

Security is dependent on a wide range of actors that are implementing technical documentation. Therefore it is crucial that language is clear, and understood by all that need to implement this documentation. Correct and inclusive language is therefore conducive for secure implementations of technical documentation. 

# IANA Considerations

This document has no actions for IANA.

