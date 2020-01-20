---
title: Draft list of requirements
toc: true
type: docs
draft: false
menu:
  docs:
    parent: Document pool
    weight: 5
weight: 5
---

I find these loosely differentiated categories meaningful to set requirements for Estonian e-voting. For input I mostly used:

* [Handbook for the Observation of New Voting Technologies](https://www.osce.org/odihr/elections/104939) (2013)
* [OSCE Office for Democratic Institutions and Human Rights election reports on Estonia](https://www.osce.org/odihr/elections/estonia/) (2007, 2011, 2015, 2019)
* [The Council of Europe Recommendation Rec(2017)5 on Standards for E-voting](https://search.coe.int/cm/Pages/result_details.aspx?ObjectID=0900001680726f6f) (2017)
* [A framework for comparing the security of voting schemes](https://www.attejuvonen.fi/thesis/) (2019)
* [End-to-end election verifiability for a nontechnical audience](https://arxiv.org/abs/1504.03778) (2014)
* [Verifiability Notions for E-Voting Protocols](https://eprint.iacr.org/2016/287) (2016)
* [The Future of Voting: End-to-end Verifiable Internet Voting. Specification and Feasibility Assessment Study](https://github.com/GaloisInc/e2eviv/blob/master/report/E2EVIV_full_report.pdf) (2015)
* [E-voting security work group report of Estonian Ministry of Economic Affairs and Communications](https://www.mkm.ee/sites/default/files/content-editors/e-valimiste_tooruhma_koondaruanne_12.12.2019_0.pdf) (2019, see also my [debrief initiative]( https://events.ccc.de/congress/2019/wiki/index.php/Session:Debrief_on_e-voting_in_Estonia))

Under each of the categories I intend to write detailed accounts quoting relevant reports and documents. The result will be published as [index of requirements with progress indicators](https://github.com/infoaed/evote-debrief#debrief-on-e-voting-in-estonia), which may differ from requirements of any particular system, but should create a framework to assess those systems in relation to an ideal.

## Legal

* The goals of e-voting are clearly defined and rigorously assessed by introducing body
* The principles for e-voting are established based on common understanding of public interest groups and parties running in elections
* Legality of principles has been assessed and approved by constitutional authority
* Universal, free, fair, equal, direct and observable elections with secret voting are guaranteed
* Roles and responsibilities are clearly set and developments are regularly monitored by legal authority

## Safeguards

* E-voting is politically neutral, non-discriminative and trustworthy channel of voting
* Voters have access to technology, proper levels of digital literacy and their digital rights are ensured 
* Hazards of voting in an uncontrolled environment are met with proper legal, technological etc measures
* Process of e-voting is comprehensive in all aspects and technological solution provides full support for the voting protocol with proper guidance
* Reference materials thoroughly explain e-voting process, providing voters with means for dispute resolution and defense against threats specific to electronic voting channel

## Verification

* Voter can make sure her choice was cast as intended, recorded as cast and counted as recorded
* Voter's choice is secret throughout the process and there no way to prove a particular vote belonging to a voter
* Tallying of the votes is observable in a way that voters and observers can verify that only votes of eligible voters were counted and none of them was missed
* Local and international observers have full access to means of verification without a need to rely on operator or tools provided
* Robust and comprehensive end-to-end verifiability is provided starting from casting of the vote up to publishing of the election results

## Development

* All documentation from memos of meetings to official reports on legal, procurement, analysis, evaluation, software, hardware, protocol etc aspects of e-voting is public, correct and easily approachable
* E-voting is developed according to its publicly agreed goals based on long-term schedule enabling participation of local and international interest groups
* Contracting authority has full understanding of technological as well as legal requirements, choices made during development are motivated and explained as such in documentation
* Resources provided for development are stable and proportional, there is no conflicts of interest between contracting authority, research providers and developers, procurements are public and inclusive
* Electronic voting is developed with a future perspective to be compatible with technological advancements and requirements for digital democracy 

## Technology

* Technical risks related to software and hardware are systematically addressed according to written rules derived from security analysis based on legal and technical requirements
* Integration with information systems providing list of voters, authentication, client drivers, etc. take into account the security and accountability standards specific to e-voting
* Dependency to libraries, protocols and other software solutions follows the security standards, dependency to software controlled by third parties is minimal
* Source code of all components of the e-voting system is published along with the documentation following dedicated open source licenses and best practices
* User interfaces take into account the need for platform neutrality, accessibility, usability requirements, no unneeded limitations for platform, Internet connection, etc. are forced on voters
* The e-voting system is tested, audited and certified before using in elections, all its components have endured public scrutiny and intrusion testing

## Procedure

* There are strict physical and technical rules of procedure, which are followed, steps taken are logged and reported by the operator of the system
* There are precise and clear procedures for election observers to be able to observe all the processes involved and to file complaints
* Disputes are efficiently solved based on clear rules, there is a purposeful chain of responsibility that guarantees that all problems are adequately solved, issues and solutions are documented
* System enables observers to check in real time if hardware and software is operating correctly using logs, dashboards and other means of introspection
* Conducting of e-voting is audited by amount of independent parties, gathering the lists of voters, collecting the hardware, compiling the software and running the system is auditable in detail during and after the election
* Tallying the votes and publishing the results is done in clear and non-discriminative way, the data is available for every interested party on the equal basis

## Standards

* E-voting follows national and international standards, recommendations and best practices
* Recommendations of national and international election experts are documented, discussed and taken into account where applicable
* Solutions for legal and technological issues are sought in the framework of current scientific research

