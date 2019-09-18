---
title: Notes on networking standards and politics
abbrev: politix
docname: draft-irtf-hrpc-political-05
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

   RFC0049:
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
   RFC8280:

   BramanI:
     title: "Internationalization of the Internet by design: The first decade"
     date: 2012
     author:
        - ins: S. Braman
     target: http://dx.doi.org.proxy.uba.uva.nl:2048/10.1177%2F1742766511434731
     seriesinfo: "Global Media and Communication, Vol 8, Issue 1, pp. 27 - 45"

   BramanII:
     title: "The Framing Years: Policy Fundamentals in the Internet Design Process, 1969–1979"
     date: 2010
     author:
        - ins: S. Braman
     target: http://dx.doi.org.proxy.uba.uva.nl:2048/10.1080/01972243.2011.607027
     seriesinfo: "The Information Society Vol. 27, Issue 5, 2011"

   Contreras:
     title:  "Technical Standards and Ex Ante Disclosure: Results and Analysis of an Empirical Study"
     date: 2013
     author:
        - ins: J.L. Contreras
     target:
     seriesinfo: "Jurimetrics: The Journal of Law, Science &amp; Technology, vol. 53, p. 163-211"

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

   RogersEden:
      title: "The Snowden Disclosures, Technical Standards, and the Making of Surveillance Infrastructures"
      date: 2017
      author:
        - ins: M. Rogers
        - ins: G. Eden
      seriesinfo: "International Journal of Communication 11(2017), 802-823"
      target: "http://ijoc.org/index.php/ijoc/article/view/5525/1941"

   CJEU2004:
      title: "ECLI:EU:C:2004:257, C-418/01 IMS Health"
      date: 2004
      author:
        - ins: Court of Justice of the European Union
      target: "http://curia.europa.eu/juris/liste.jsf?num=C-418/01"
      seriesinfo: "Cambridge, UK: Cambridge University Press"

   CJEU2007:
      title: "ECLI:EU:T:2007:289, T-201/04 Microsoft Corp."
      date: 2007
      author:
        - ins: Court of Justice of the European Union
      target: "http://curia.europa.eu/juris/liste.jsf?num=T-201/04"
      seriesinfo: "Cambridge, UK: Cambridge University Press"

   Ahlborn:
      title: "Implications of the Proposed Framework and Antitrust Rules for Dynamically Competitive Industries"
      date: 2006
      author:
        - ins: C. Ahlborn
        - ins: V. Denicoló
        - ins: D. Geradin
        - ins: A.J. Padilla
      target: "http://curia.europa.eu/juris/liste.jsf?num=T-201/04"
      seriesinfo: "DG Comp’s Discussion Paper on Article 82, DG COMP, European Commission"

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



--- abstract

The IETF cannot ordain what standards or protocols are to be used on networks, but the standards development process in the IETF does have an impact on society through its normative standards setting process. This document aims to bring about a better understanding on the political nature of standards and protocols. Among other things, the IETF's work affects what is perceived as technologically possible and useful where networking technologies are being deployed, and its standards reflect what is considered by the technical community to be feasible and good practice. Whereas there might not be agreement among the Internet protocol community on the specific political nature of the technological development process and its outputs, it is undisputed that standards and protocols are both products of a political process, and they can also be used for political means.

--- middle

Introduction
============

    "Science and technology lie at the heart of social asymmetry.
       Thus technology both creates systems which close off other
       options and generate  novel, unpredictable and indeed
       previously unthinkable, option. The game of technology is
       never finished, and its ramifications are endless."

                                   - Michel Callon

    "The Internet isn't value-neutral, and neither is the IETF."

                                   -{{RFC3935}}

Recently there has been increased discussion in the IRTF and IETF on the relation between Internet protocols and human rights {{RFC8280}}, which spurred discussion of the value neutrality and political nature of standards. The network infrastructure is on the one hand designed, described, developed, standardized and implemented by the Internet community, while on the other hand the Internet community and Internet users are also shaped by the affordances of the technology. Companies, citizens, governments, standards development bodies, public opinion and public interest groups all play a part in these discussions. This document outlines different views on the relation between politics, standards, and protocols, and seeks to answer the question of whether standards and protocols are political, and if so, how.

This question in not necessarily a new one. The design of the Internet through protocols and standards is a technical issue with great political and economic impacts, as is described in {{RFC0613}} and {{RFC3271}}. The early Internet community already realized that it needed to make decisions on political issues such as: 

* internationalization {{BramanI}}; 
* access {{RFC0101}}; 
* security {{RFC0049}}; 

as well as use of the network by different groups with different needs and requirements, such as:

* the military {{RFC0164}} {{RFC0316}}, 
* governments {{RFC0144}} {{RFC0286}} {{RFC0313}} {{RFC0542}} {{RFC0549}} 
* and non-governmental entities {{RFC0196}}.

This has been clearly shown in the work done by Sandra Braman {{BramanII}}. This documents builds on that research and seeks to increase unstanding about what this means in the context of Internet protocols and the entities that design, develop, and standardize them. 

Vocabulary Used
===============

Politics
: (from Greek: Politiká: Politika, definition "affairs of the commons") is the process of making decisions applying to all members of a diverse group with conflicting interests. More narrowly, it refers to achieving and exercising positions of governance or organized control over a community. Furthermore, politics is the study or practice of the distribution of power and resources within a given community as well as the interrelationship(s) between communities. (adapted from {{HagueHarrop}})

Affordances
: The possibilities that are provided to an actor through the ordering of an environment by a technology. This means that a technology does not determine what is possible, but that it that invites specific kinds of behavior, and in that process shapes it.

Protocols  
: 'Protocols are rules governing communication between devices or applications, and the creation or manipulation of any logical or communicative artifacts concomitant with such communication.' {{Sisson}}

Standard
: 'A standard is an agreed-upon way of doing something or measuring something.' {{Sisson}}

Internet Standards  
: 'An Internet Standard is a specification that is stable and well-understood, is technically competent, has multiple, independent, and interoperable implementations with substantial operational experience, enjoys significant public support, and is recognizably useful in some or all parts of the Internet.' {{RFC2026}}


Research Question
=================

To bring about a better understanding on the political nature of standards and protocols, this documents asks the questions: If, and if so how, are protocols, standards, and politics interrelated? Answering this question aims to inform discussions in the IETF, IRTF, and the wider Internet infrastructure and architecture community.


Technology and Politics: a review of literature and community positions
=======================================================================

In 1993 the Computer Professionals for Social Responsibility stated that 'the Internet should meet public interest objectives'. Similarly, {{RFC3935}} states that 'The Internet isn't value-neutral, and neither is the IETF.'. Ethics and the Internet was already a topic of an RFC by the IAB in 1989 {{RFC1087}}. Nonetheless there has been a recent uptick in discussions within the IETF and IRTF about the impact of Internet protocols on human rights {{RFC8280}}, and more generally in public debate about the impact of technology on society.

This document aims to provide an overview of the spectrum of different positions that have been observed in the IETF and IRTF community, and have been observed during interviews, mailinglist exchanges, and during research group sessions. These positions were observed during participatory observation, through 39 interviews with members of the community, the Human Rights Protocol Considerations Research Group mailing list, and during and after the Technical Plenary on Protocols and Human Rights during IETF98.

Without judging them on their internal or external consistency they are represented here. Where possible we also sought to engage with the academic literature on this topic.

## Technology is value neutral
This position starts from the premise that the technical and political are differentiated fields and that technology is 'value free'. This is also put more explicitly by Carey: "electronics is neither the arrival of apocalypse nor the dispensation of  grace.  Technology  is  technology;  it  is  a  means  for  communication  and  transportation  over  space, and nothing more." {{Carey}}. In this view protocols only become political when it is actually being used by humans. So the technology itself is not political, the use of the technology is. This view sees technology as instrument; "technologies  are  'tools' standing  ready  to  serve  the  purposes  of  their  users.  Technology  is  deemed  'neutral,' without valuative content of its own.'" {{Feenberg}}. Feenberg continues: "technology  is  not  inherently  good  or  bad,  and  can  be  used  to  whatever  political  or  social  ends  desired  by  the  person  or  institution  in  control.  Technology  is  a  'rational entity' and universally applicable. One may make exceptions on moral grounds, but one must also understand that the "price for the achievement of environmental, ethical, or religious goals...is reduced efficiency." {{Feenberg}}.

## Some protocols are political sometimes
This stance is a pragmatic approach to the problem. It states that some protocols under certain conditions can themselves have a political dimension.  This is different from the claim that a protocol might sometimes be used in a political way; that view is consistent with the idea of the technology being neutral (for the human action using the technology is where the politics lies).  Instead, this position requires that each protocol and use be evaluated for its political dimension, in order to understand the extent to which it is political.

## All protocols are political sometimes
While not an absolutist standpoint it recognizes that all design decisions are subject to the law of unintended consequences. The system consisting of the Internet and its users is vastly too complex to be predictable; it is chaotic in nature; its emergent properties cannot be predicted. This concept strongly hinges on the general purpose aspect of information technology and its malleability. Whereas not all (potential) behaviours, affordances and impacts of protocols can possible be predicted, one could at least consider the impact of proposed implementations.

## The network has its own logic and values
While humans create technologies, this does not mean that they are forever under human control. A technology, once created, has its own logic that is independent of the human actors that either create or use the technology.

From this perspective, technologies can shape the world. As Martin Heidegger says, "The hydroelectric plant is not built into the Rhine River as was the old wooden bridge that joined bank with bank for hundreds of years. Rather the river is dammed up into the power plant. What the river is now, namely, a water power supplier, derives from out of the essence of the power station." {{Heidegger}} (p 16)  The dam in the river changes the world in a way the bridge does not, because the dam alters the nature of the river.

In the same way -- in another and more recent example -- the very existence of automobiles imposes physical forms on the world different from those that come from the electric tram or the horse-cart. The logic of the automobile means speed and the rapid covering of distance, which encourages suburban development and a tendency toward conurbation. But even if that did not happen, widespread automobile use requires paved roads, and parking lots and structures. These are pressures that come from the automotive technology itself, and would not arise without that technology.

In much same way, then, networking technology, such as protocols, creates its own demands. One of the most important conditions for a protocol's success is its incremental deployability {{RFC5218}}.  This means that the network already contains constraints on what can be deployed into it. In this sense the network creates its own paths, but also has its own objective. According to this view the goal of the network is interconnection and connectivity; more connectivity is good for the network. Proponents of this positions also often describe the Internet as an organism with its own unique ecosystem.

In this position it is not necessarily clear where the 'social' ends and the 'technical' begins, and it could be argued that the distinction itself is a social construction {{BijkerLaw}} or that a real-life distinction between the two is hard to make {{Bloor}}.

## Protocols are inherently political
This position argues the opposite of 'technological neutrality'. This position is illustrated by Postman when he writes: "the uses made of technology are largely determined by the structure of the technology itself" {{Postman}}. He states that the medium itself "contains an ideological bias". He continues to argue that technology is non-neutral:

(1) because of the symbolic forms in which information is encoded, different media have different intellectual and emotional biases;

(2) because of the accessibility and speed of their information, different media have different political biases;

(3) because of their physical form, different media have different sensory biases;

(4) because of the conditions in which we attend to them, different media have different social biases;

(5) because of their technical and economic structure, different media have different content biases.

Recent scholars of Internet infrastructure and governance have also pointed out that Internet processes and standards have become part and parcel of political processes and public policies. Several concrete examples are found within this approach, for instance, the IANA transition or global innovation policy {{DeNardis}}. The Raven process in which the IETF refused to standardize wiretapping -- which resulted in {{RFC2804}} -- was an instance where an international governance body took a position that was largely political, although driven by a technical argument. The process that led to {{RFC7258}} is similar: the Snowden disclosures, which occured in the political space, engendered the IETF to act. This is summarized in {{Abbate}} who says: "protocols are politics by other means," emphasizing the interests that are at play in the process of designing standards.

This position further holds that protocols can never be understood without their contextual embeddedness: protocols do not exist solely by themselves but always are to be understood in a more complex context -- the stack, hardware, or nation-state interests and their impact on civil rights. Finally, this view is that protocols are political because they influence the socio-technical workings of reality and society. The latter observation leads Winner to conclude that the reality of technological progress has too often been a scenario where innovation has dictated change for society. Those who had the power to introduce a new technology also had the power to create a consumer class to use the technology "with new practices, relationships, and identities supplanting the old, --- and those who had the wherewithal to implement new technologies often molded society to match the needs of emerging technologies and organizations." {{Winner}}.

IETF: Protocols as Standards
============================

In the previous section we gave an overview of the different existing positions of the impact of Internet protocols in the Internet protocol community. In the following section we will review the standards setting process and its consequences for the politics of protocols, through the lens of existing literature on standards setting.

Standards enabling interoperating networks, what we think of today as the Internet, were created as open, formal and voluntary standards. A platform for Internet standardization, the Internet Engineering Task Force (IETF), was created in 1986 to enable the continuation of such standardization work. The IETF has sought to make the standards process transparent (by ensuring everyone can access standards, mailing-lists and meetings), predictable (by having clear procedures and reviews) and of high quality (by having draft documents reviewed by experts from its own community). This is all aimed at increasing the accountability of the process and the quality of the standard.

The IETF implements what has been referred to as an "informal ex ante disclosure policy" for patents {{Contreras}}, which includes the possibility for participants to disclose the existence of a patent relevant for the standard, royalty-terms which would apply to the implementers of that standard should it enter into effect, as well as other licensing terms that may be interesting for implementers to know. The community ethos in the IETF seems to lead to 100% royalty-free disclosures of prior patents which is a record number, even among other comparable standard organizations {{Contreras}}. In the following paragraph we will describe inherent tensions in the standards process.

## Competition and collaboration

Standards exist for nearly everything: processes, technologies, safety, hiring, elections, and training. Standards provide blue-prints for how to accomplish a particular task in a similar way for others that are trying to accomplish the same thing, while reducing overhead and inefficiencies. Although there are different types and configurations of standards, they all enhance competition by allowing different entities to work from a commonly accepted baseline.

On the first types of standards than can be found are "informal" ones -- agreed-upon normal ways of interacting within a specific community. For example, the process through which greetings to a new acquaintance are expressed through a bow, a handshake or a kiss. On the other hand, "formal" standards are normally codified in writing.

Within economy studies, _de facto_ standards arise in market situations where one entity is particularly dominant; downstream competitors are therefore tied to the dominant entity's technological solutions {{Ahlborn}}. Under EU anti-trust law, _de facto_ standards have been found to restrict competition for downstream services in PC software products {{CJEU2007}}, as well as downstream services dependent on health information {{CJEU2004}}.

Even in international law, the World Trade Organization (WTO) uses standards, although it recognizes a difference between standards and technical regulations. The former are voluntary formal codes to which products or services may conform, while technical regulations are mandatory requirements to be fullfilled for a product to be accessible in a national market. These rules have implications for how nation states bound by WTO agreements can impose specific technical requirements on companies. Nonetheless, there are many standardization groups that were originally launched by nation states or groups of nation states. ISO, BIS, CNIS, NIST, ABNT and ETSI are examples of institutions that are, wholly or partially, sponsored by public money in order to ensure the smooth development of formal standards. Even if under WTO rules these organizations cannot create the equivalent of a technical regulation, they have important normative functions in their respective countries. No matter what form, all standards enhance competition and collaboration because they define a common approach to a problem. This potentially allows different instances to interoperate or be evaluated according to the same indicators.

The development of formal standards faces a number of economic and organizational challenges. Mainly, the cost and difficulty of organizing many entities around a mutual goal, as well as the cost of research and development leading up to a mutually beneficial technological platform. In addition, deciding what the mutual goal is can also be a problem. These challenges may be described as inter-organizational costs. Even after a goal is decided upon, coordination of multiple entities requires time and money. One needs communication platforms, processes and a commitment to mutual investment in a higher good. They are not simple tasks, and the more different communities are affected by a particular standardization process, the more difficult the organizational challenges become.

## How voluntary are open standards?

Coordinating transnational stakeholders in a process of negotiation and agreement through the development of common rules is a form of global governance {{Nadvi}}. Standards are among the mechanisms by which this governance is achieved. Conformance to certain standards is often a basic condition of participation in international trade and communication, so there are strong economic and political incentives to conform, even in the absence of legal requirements {{Russell}}. {{RogersEden}} argue:

   "As unequal participants compete to define standards, technological compromises emerge, which add complexity to standards. For instance, when working group participants propose competing solutions, it may be easier for them to agree on a standard that combines all the proposals rather than choosing any single proposal. This shifts the responsibility for selecting a solution onto those who implement the standard, which can lead to complex implementations that may not be interoperable. On its face this appears to be a failure of the standardization process, but this outcome may benefit certain participants -- for example, by allowing an implementer with large market share to establish a _de facto_ standard within the scope of the documented standard."

Conclusion
==========

Economics, competition, collaboration, openness, and political impact have been an inherent part of the work of the IETF since its early beginnings {{Russell}} {{BramanII}} {{Abbate}}. The IETF cannot ordain which standards are to be used on the networks, and it specifically does not determine the laws of regions or countries where networks are being used, but it does set open standards for interoperability on the Internet, and has done so for many of the Internet's formative years. Because a standard is the blue-print for how to accomplish a particular task, the adopted standards have a normative effect. The standardization work at the IETF has direct implications on what is perceived as technologically possible and useful where networking technologies are being deployed, and thus its standards reflect what is considered by the technical community as feasible and good practice. 

Whereas there might not be agreement among the Internet protocol community on the specific political nature of the technological development process and its outputs, it is undisputed that standards and protocols are both products of a political process, and they can also be used for political means. Therefore protocols and standards are not 'value-neutral, and neither is the IETF' {{RFC3935}}. 

While 'standards emerge from contested contexts, they immediatly function as a means of control within the political and economic order' {{Russell}}, protocols and standards as abstract isolated artefacts might not be political, but their design, development, deployment, and implementation is. Therefore we might need to give a qualified answer to the research question, in the sense that protocols can never be understood outside of their actual shaping, use, and function, which is inherently political. 

Further research could explore how the political nature of the design, development, standardization, and deployment of protocols can be taken into account in the standards development process in order to (1) to minimize negative unintended social consequences, (2) ensure clear understanding of the intended consequences, (3) maintain importance of the IETF as open standards body that facilitates global interoperability.

Security Considerations
=======================

As this draft concerns a research document, there are no security considerations as described in {{RFC3552}}, which does not mean that not addressing the issues brought up in this draft will not impact the security of end-users or operators.

IANA Considerations
===================

This document has no actions for IANA.


Acknowledgements
================

Thanks to Michael Rogers, Joe Hall, Andrew Sullivan, Brian Carpenter, Mark Perkins, S Moonesamy and all contributors and reviewers on the hrpc mailinglist. Special thanks to Gisela Perez de Acha for some thorough editing rounds, and Amelia Andersdotter for text contributions.

Research Group Information
==========================

The discussion list for the IRTF Human Rights Protocol Considerations Research Group is located at the e-mail address <hrpc@ietf.org>. Information on the group and information on how to subscribe to the list is at:
<https://www.irtf.org/mailman/listinfo/hrpc>

Archives of the list can be found at:
<https://www.irtf.org/mail-archive/web/hrpc/current/index.html>
