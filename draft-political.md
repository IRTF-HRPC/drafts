---
title: Notes on networking standards and politics
abbrev: politix
docname: draft-irtf-hrpc-political-07
category: info

ipr: trust200902
area: IRTF
workgroup: Human Rights Protocol Considerations Research Group
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
       ins: N. ten Oever
       name: Niels ten Oever
       organization: University of Amsterdam
       email: mail@nielstenoever.net

normative:

informative:

   RFC0101:
   RFC0144:
   RFC0164:
   RFC0196:
   RFC0286:
   RFC0313:
   RFC0316:
   RFC0542:
   RFC0549:
   RFC0613:
   RFC1087:
   RFC2026:
   RFC2804:
   RFC3271:
   RFC3552:
   RFC3935:
   RFC5218:
   RFC7258:
   RFC7858:
   RFC8226:
   RFC8280:
   RFC8404:

   BramanI:
     title: "Internationalization of the Internet by design: The first decade"
     date: 2012
     author:
        - ins: S. Braman
     target: http://people.tamu.edu/~Braman/bramanpdfs/43_internationalization.pdf
     seriesinfo: "Global Media and Communication, Vol 8, Issue 1, pp. 27 - 45"

   BramanII:
     title: "The Framing Years: Policy Fundamentals in the Internet Design Process, 1969–1979"
     date: 2010
     author:
        - ins: S. Braman
     target: http://people.tamu.edu/~Braman/bramanpdfs/50_theframingyears.pdf
     seriesinfo: "The Information Society Vol. 27, Issue 5, 2011"

   BramanIII:
     title: "Privacy by design: Networked computing, 1969-1979"
     date: 2011
     author:
        - ins: S. Braman
     target: http://people.tamu.edu/~Braman/bramanpdfs/59_privacybydesign.pdf
     seriesinfo: "New Media & Society, 14(5), 798-814, 2011."

   Feenberg:
     title: Critical Theory of Technology
     date: 1991
     author:
       - ins: A. Feenberg
     seriesinfo: p.5-6

   Carey:
     title: Communication As Culture
     date: 1992
     author:
       - ins: J. Carey
     seriesinfo: p. 139

   Postman:
     title: "Technopoly: the Surrender of Culture to Technology"
     date: 1992
     author:
       - ins: N. Postman
     seriesinfo: "Vintage: New York. pp. 3–20."

   DeNardis:
     title: The Internet Design Tension between Surveillance and Security
     date: 2015
     author:
       - ins: L. Denardis
     target: http://is.gd/7GAnFy
     seriesinfo: IEEE Annals of the History of Computing (volume 37-2)

   Winner:
     title: Who will we be in cyberspace?
     date: 1995
     author:
         - ins: L. Winner
     target: iwcenglish1.typepad.com/iwc_media_ecology/Documents/Who_will_we_be_in_cyberspace.doc

   Abbate:
      title: Inventing the Internet
      date: 2000
      author:
        - ins: J. Abbate
      target: https://mitpress.mit.edu/books/inventing-internet
      seriesinfo: MIT Press

   Heidegger:
      title: "The Question Concerning Technology and Other Essays"
      date: 1977
      author:
        - ins: M. Heidegger
      target: "http://ssbothwell.com/documents/ebooksclub.org__The_Question_Concerning_Technology_and_Other_Essays.pdf"
      seriesinfo: "Garland: New York, 1977"

   Nadvi:
      title: Making sense of global standards
      date: 2004
      author:
        - ins: K. Nadvi
        - ins: F. Wältring
      seriesinfo: "In: H. Schmitz (Ed.), Local enterprises in the global economy (pp. 53–94). Cheltenham, UK: Edward Elgar."

   Russell:
      title: "Open standards and the digital age: History, ideology, and networks"
      date: 2014
      author:
        - ins: A.M. Russell
      seriesinfo: "Cambridge, UK: Cambridge University Press"

   Winner:
      title: "Upon opening the black box and finding it empty: Social constructivism and the philosophy of technology"
      date: 1993
      author:
        - ins: L. Winner
      seriesinfo: "Science, Technology, and Human Values 18 (3) p. 362-378"

   HagueHarrop:
     title: "Comparative Government and Politics: An Introduction"
     date: 2013
     author:
        - ins: R. Hague
        - ins: M. Harrop
     seriesinfo: "Macmillan International Higher Education. pp. 1–. ISBN 978-1-137-31786-5."

   BijkerLaw:
     title: "Shaping Technology/ Building Society: Studies in Sociotechnical Change"
     date: 1992
     author:
        - ins: W. Bijker
        - ins: J. Law
     seriesinfo: "Cambridge, MA: MIT Press"

   Bloor:
     title: Knowledge and Social Imagery
     date: 1976
     author:
        - ins: D. Bloor
     seriesinfo: "London: Routeledge & Kegan Paul"

   Sisson:
     title: Standards and Protocols
     date: 2000
     author:
        - ins: D. Sisson
     target: https://philosophe.com/design/standards/

   Barney:
     title: One nation under google
     date: 2007
     author:
        - ins: D. Barney
     target: http://darinbarneyresearch.mcgill.ca/Work/One_Nation_Under_Google.pdf
     seriesinfo: Hart House Lecture 2007


--- abstract

The IETF cannot ordain what standards or protocols are to be used on networks, but the standards development process in the IETF does have an impact on society through its normative standards setting process. This document aims to bring about a better understanding on the political nature of standards and protocols. Among other things, the IETF's work affects what is perceived as technologically possible and useful where networking technologies are being deployed, and its standards reflect what is considered by the technical community to be feasible and good practice. Whereas there might not be agreement among the Internet protocol community on the specific political nature of the technological development process and its outputs, it is generally agreed that standards and protocols are both products of a political process, and they can also be used for political means.

--- middle

Introduction
============

    "Standards are recipes for reality."

                                   - Lawrence Busch

    "As standards emerge from contested contexts, that
       immediately function as a means of control within the
            political and economic order."

                                   - Andrew L. Russell

    "The Internet isn't value-neutral, and neither is the IETF."

                                   - {{RFC3935}}

Recently there has been increased discussion in the IRTF and IETF on the relation between Internet protocols and human rights {{RFC8280}}, which spurred discussion of the value neutrality and political nature of standards. The network infrastructure is on the one hand designed, described, developed, standardized and implemented by the Internet community, while on the other hand the Internet community and Internet users are affected by the technology. Companies, citizens, governments, standards development bodies, public opinion and public interest groups all play a part in these discussions. This document outlines different views on the relation between politics, standards, and protocols, and seeks to explore the question whether standards and protocols are political, and if so, how.

This question in not necessarily a new one. The design of the Internet, and its codification through protocols and standards, is a technical issue with great political and economic impacts, as is described in {{RFC0613}} and {{RFC3271}}. The early Internet community already realized that it needed to make decisions on political issues such as:

* internationalization, expanding the network outside of the United States {{BramanI}};
* access, how people are able to access the network, and who has control {{RFC0101}};
* privacy and security, what level of secrecy should be considered and expected on the network {{BramanIII}};

as well as use of the network by different groups with different needs and requirements, such as:

* the military {{RFC0164}} {{RFC0316}};
* governments {{RFC0144}} {{RFC0286}} {{RFC0313}} {{RFC0542}} {{RFC0549}};
* and non-governmental entities {{RFC0196}}.

Sandra Braman has foregrounded these political considerations in historical RFCs in her extensive analysis of these documents {{BramanII}}. This document seeks to understand how this is relevant for current day Internet standardization and protocol design. The coordinating of transnational stakeholders in a process of negotiation and agreement through the development of common rules is a form of global governance {{Nadvi}}. Standards are among the mechanisms by which this governance is achieved, although this process is not exclusively undertaken by transnational corporations. Conformance to certain standards is often a basic condition of participation so there are strong economic and political incentives to conform, even in the absence of legal requirements {{Russell}}.

This documents builds on that research and seeks to increase understanding about what this means in the context of Internet protocols and the entities that design, develop, and standardize them.


Vocabulary Used
===============

Politics
: (from Greek: Politiká: Politika, definition "affairs of the commons") is the process of making decisions applying to all members of a diverse group with conflicting interests. More narrowly, it refers to achieving and exercising positions of governance or organized control over a community. Furthermore, politics is the study or practice of the distribution of power and resources within a given community as well as the interrelationship(s) between communities. (adapted from {{HagueHarrop}})

Affordances
: The possibilities that are provided to an actor through the ordering of an environment by a technology. This means that a technology does not determine what is possible, but that it invites specific kinds of behavior, and in that process shapes the behavior of users, without aboslutely determining it.

Protocols
: 'Protocols are rules governing communication between devices or applications, and the creation or manipulation of any logical or communicative artifacts concomitant with such communication.' {{Sisson}}

Standards
: 'A standard is an agreed-upon way of doing something or measuring something.' {{Sisson}}

Internet Standards
: 'An Internet Standard is a specification that is stable and well-understood, is technically competent, has multiple, independent, and interoperable implementations with substantial operational experience, enjoys significant public support, and is recognizably useful in some or all parts of the Internet.' {{RFC2026}}


Research Question
=================

To bring about a better understanding on the political nature of standards and protocols, this documents asks the questions: If, and if so how, are protocols, standards, and politics interrelated? Exploring this question aims to inform discussions in the IETF, IRTF, and the wider Internet infrastructure and architecture community.


Technology and Politics: a review of literature and community positions
=======================================================================

In 1993 the Computer Professionals for Social Responsibility stated that 'the Internet should meet public interest objectives'. Similarly, {{RFC3935}} states that 'The Internet isn't value-neutral, and neither is the IETF.'. Ethics and the Internet was already a topic of an RFC by the IAB in 1989 {{RFC1087}}, when the Internet was still looking entirely different. Nonetheless there has been a recent uptick in discussions within the IETF and IRTF about the impact of Internet protocols on human rights {{RFC8280}}, and more generally in public debate about the impact of technology on society.

This document aims to provide an overview of the spectrum of different positions that have been observed in the IETF and IRTF community, and have been observed during interviews, mailinglist exchanges, and during research group sessions. These positions were observed during participatory observation, through 39 interviews with members of the community, the Human Rights Protocol Considerations Research Group mailing list, and during and after the Technical Plenary on Protocols and Human Rights during IETF98.

Without judging them on their internal or external consistency they are represented here. Where possible we also sought to engage with the academic literature on this topic.

## Technology is value neutral
This position starts from the premise that the technical and political are differentiated fields and that technology is 'value free'. This is also put more explicitly by Carey: "electronics is neither the arrival of apocalypse nor the dispensation of  grace.  Technology  is  technology;  it  is  a  means  for  communication  and  transportation  over  space, and nothing more." {{Carey}}. In this view protocols only become political when it is actually being used by humans. So the technology itself is not political, the use of the technology is. This view sees technology as instrument; "technologies  are  'tools' standing  ready  to  serve  the  purposes  of  their  users.  Technology  is  deemed  'neutral,' without valuative content of its own.'" {{Feenberg}}. Feenberg continues: "technology  is  not  inherently  good  or  bad,  and  can  be  used  to  whatever  political  or  social  ends  desired  by  the  person  or  institution  in  control.  Technology  is  a  'rational entity' and universally applicable. One may make exceptions on moral grounds, but one must also understand that the "price for the achievement of environmental, ethical, or religious goals...is reduced efficiency." {{Feenberg}}.

## Some protocols are political sometimes
This stance is a pragmatic approach to the problem. It states that some protocols under certain conditions can themselves have a political dimension.  This is different from the claim that a protocol might sometimes be used in a political way; that view is consistent with the idea of the technology being neutral (for the human action using the technology is where the politics lies).  Instead, this position implies that protocols could be evaluated for its political dimension, in order to understand the extent to which it is political.

## All protocols are political sometimes
While not an absolutist standpoint it recognizes that all design decisions are subject to the law of unintended consequences, especially in a context where the interrelation between protocols is hard to predict. The system consisting of the Internet and its users is vastly complex; it is chaotic in nature; standards are voluntary; and therefore its emergent properties cannot be predicted. This concept strongly hinges on the general purpose aspect of information technology and its malleability. Whereas not all (potential) behaviours, affordances and impacts of protocols can possibly be predicted, one could, as a point of departure, consider the impact of proposed implementations.

## The network of networks has its own logic and values
While humans create technologies, this does not mean that they are forever under human control. A technology, once created, has its own logic that is independent of the human actors that either create or use the technology.

From this perspective, technologies can shape the world. As Martin Heidegger says, "The hydroelectric plant is not built into the Rhine River as was the old wooden bridge that joined bank with bank for hundreds of years. Rather the river is dammed up into the power plant. What the river is now, namely, a water power supplier, derives from out of the essence of the power station." {{Heidegger}} (p 16)  The dam in the river changes the world in a way the bridge does not, because the dam alters the nature of the river.

In the same way -- in another and more recent example -- the very existence of automobiles imposes physical forms on the world different from those that come from the electric tram or the horse-cart. The logic of the automobile means speed and the rapid covering of distance, which encourages suburban development and a tendency toward conurbation. But even if that did not happen, widespread automobile use requires paved roads, and parking lots and structures. These are pressures that come from the automotive technology itself, and would not arise without that technology.

In much same way, then, networking technology, such as protocols, creates its own demands. One of the most important conditions for a protocol's success is its incremental deployability {{RFC5218}}.  This means that the network already contains constraints on what can be deployed into it. In this sense the network of networks creates its own paths, but also has its own objective. According to this view the goal of the network of networks is interconnection and connectivity; more connectivity is good for the network of networks. Proponents of this positions also often describe the Internet as an organism with its own unique ecosystem.

In this position it is not necessarily clear where the 'social' ends and the 'technical' begins, and it could be argued that the distinction itself is a social construction {{BijkerLaw}} or that a real-life distinction between the two is hard to make {{Bloor}}.

## Protocols are inherently political
This position argues the opposite of 'technological neutrality'. This position is illustrated by Postman when he writes: "the uses made of technology are largely determined by the structure of the technology itself" {{Postman}}. He states that the medium itself "contains an ideological bias". He continues to argue that technology is non-neutral:

(1) because of the symbolic forms in which information is encoded;

(2) because of the accessibility and speed of their information, different media have different political biases;

(3) because of their physical form, different media have different sensory biases;

(4) because of the conditions in which we attend to them, different media have different social biases;

(5) because of their technical and economic structure, different media have different content biases.

Recent scholars of Internet infrastructure and governance have also pointed out that Internet processes and standards have become part and parcel of political processes and public policies. Several concrete examples are found within this approach, for instance, the IANA transition or global innovation policy {{DeNardis}}. The Raven process in which the IETF refused to standardize wiretapping -- which resulted in {{RFC2804}} -- was an instance where an international governance body took a position that was perceived by many as political, although driven by a technical argument. The process that led to {{RFC7258}} is similar: the Snowden disclosures, which occurred in the political space, engendered the IETF to act. While {{RFC2804}} was a statement about how a protocol for wiretapping would _not_ be developed, {{RFC7258}} was a statement that contributed to the development of protocols such as {{RFC7858}}, {{RFC8226}}, and {{RFC8404}}. The impact of political tensions on protocol development is summarized in {{Abbate}} who says: "protocols are politics by other means," emphasizing the interests that are at play in the process of designing standards.

This position further holds that protocols can never be understood without their contextual embeddedness: protocols do not exist solely by themselves but always are to be understood in a more complex context -- the stack, hardware, or nation-state interests and their impact on civil rights. Finally, this view is that protocols are political because they influence the socio-technical workings of reality and society. The latter observation leads Winner to conclude that the reality of technological progress has too often been a scenario where innovation has dictated change for society. Those who had the power to introduce a new technology also had the power to largely frame the uses of the technology "with new practices, relationships, and identities supplanting the old, --- and those who had the wherewithal to implement new technologies often molded society to match the needs of emerging technologies and organizations." {{Winner}}.

Discussion
==========

Economics, competition, collaboration, openness, and political impact have been an inherent part of the work of the IETF since its early beginnings {{Russell}} {{BramanII}} {{Abbate}}. The IETF cannot ordain which standards are to be used on the networks, and it specifically does not determine the laws of regions or countries where networks are being used, but it does set open standards for interoperability on the Internet, and has done so for many of the Internet's formative years. Because a standard is the blue-print for how to accomplish a particular task, the adopted standards have a normative effect. The standardization work at the IETF has direct implications on what is perceived as technologically possible and useful where networking technologies are being deployed, and thus its standards reflect what is considered by the technical community as feasible and good practice.

Whereas there might not be agreement among the Internet protocol community on the specific political nature of the technological development process and its outputs, there is a general consensus among scholars in the fields of Science and Technology Studies and Philosopht of Technology, that technology in general, and standards in specific can be:

* a mean for political activity (for instance by using a tool (or protocol) to suppress freedom of expression or enhance citizenship participation),
* an object of political activity or deliberation (this can be foregrounded by asking who is making the decision about protocols? Is it democratic and legitimate? Who is excluded in these spaces of decision about protocols/standards? Who should be included, why, and how?), ans as
* the setting of political activity (this is analyzing by asking what are the constraints and possibilities of our particular technological culture? How is the history of this technological culture affecting our choices today? {{Barney}}

This opinion is not widely shared with the IRTF and IETF. There it is generally agreed that standards and protocols can be products of a political process, and they can be used for political means, but that this is not always the case.

Conclusion
==========

While understanding that 'standards emerge from contested contexts, they immediately function as a means of control within the political and economic order' {{Russell}}, protocols and standards as abstract isolated artefacts might not be political, but their design, development, deployment, and implementation often is. Therefore we might need to give a qualified answer to the research question, in the sense that protocols can only be understood in part outside of their actual shaping, use, and applied function, which is political. There is no consensus with the Human Rights Protocol Consideration Research Group whether this is always the case, or only in specific cases.

Further research could explore how the political nature of the design, development, standardization, and deployment of protocols can be taken into account in the standards development process in order to (1) to minimize negative unintended social consequences, (2) ensure clear understanding of the intended consequences, (3) maintain importance of the IETF as open standards body that facilitates global interoperability.

Security Considerations
=======================

As this draft concerns a research document, there are no security considerations as described in {{RFC3552}}; however, the issues brought up in this document have an impact on the security of end-users or operators.

IANA Considerations
===================

This document has no actions for IANA.


Acknowledgments
================

Thanks to Michael Rogers, Joe Hall, Andrew Sullivan, Brian Carpenter, Mark Perkins, S Moonesamy, Stephen Farrell, Amelia Andersdotter, Stephane Couture, and all contributors and reviewers on the hrpc mailinglist. Special thanks to Gisela Perez de Acha for some thorough editing rounds.

Research Group Information
==========================

The discussion list for the IRTF Human Rights Protocol Considerations Research Group is located at the e-mail address <hrpc@ietf.org>. Information on the group and information on how to subscribe to the list is at:
<https://www.irtf.org/mailman/listinfo/hrpc>

Archives of the list can be found at:
<https://www.irtf.org/mail-archive/web/hrpc/current/index.html>
