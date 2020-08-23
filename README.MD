# Mathemathical approach to human intelligence augmentation

Warning: the doc is being under development and updated regularly. Feel free to propose suggestions and leave comments via issues.

<a name="table-of-contents"></a>
## Table of contents 

- [Table of contents](#table-of-contents)
- [Abstract](#abstract)
- [Introduction](#introduction)
- [Rationale](#rationale)
- [Specification](#specification)
- &nbsp;&nbsp;&nbsp;&nbsp;[Brief description](#specification-brief-description)
- &nbsp;&nbsp;&nbsp;&nbsp;[Technical requirements](#specification-technical-requirements)
- &nbsp;&nbsp;&nbsp;&nbsp;[Design requirements](#specification-design-requirements)
- [Observations of the world around us](#observations)
- &nbsp;&nbsp;&nbsp;&nbsp;[Applications](#observations-applications)
- &nbsp;&nbsp;&nbsp;&nbsp;[Use cases](#observations-use-cases)
- [Implementation](#implementation)
- &nbsp;&nbsp;&nbsp;&nbsp;[Stack](#implementation-software-stack)
- [References](#references)
- [Licence](#licence)

<a name="abstract"></a>
## Abstract

The goal is to design database of personal knowledge. Lot of people – software developers, writers, actors, teachers, artists do the only thing – reproduce, processes and creates new information. From some perspective knowledge can be seen as graph, and the goal is to find approach, that will connect all the personal knowledge of individuals into one community knowledge.

<a name="introduction"></a>
## Introduction

Human brains can't remember all the information received as an input: videos seen, articles read, theorems learned, jokes remembered – with time the brain looses memories. The reason is simple - human brain has very limited capabilites in terms of memory, we just not design to process all the information that happens around.

On the other hand computers can handle enormous amount of information. The problem is that computers yet do not "understand" data as humans does.

Our capabilities with computer interaction mostly limited not by our sensoric systems, but rather the difference in the way human brains and computers. Even direct cable to the brain won't significantly increase our intelligence. It'll increase the speed of data to be delivered to sensors, but it won't speed up the process of understanding meanings.

This document attemtps to formulate math model of human brain data processing pipline to design software that will help people to prosess large quantities of information.

<a name="rationale"></a>
## Rationale

Speach (TODO: Add links) is the main form of communication between humans either in oral or written form. Every language can be decomposed into alphabet, words, and sentences. The could be only countable number of all possible sentences (TODO: Add link to proof/explanation), meaning that humans can describe only countable amount of things, while we already know that there exists uncountable sets. It means that we must find a way to simplify the world and use even not countable, but finite number of symbols to be able to discribe what we see.

Unfortunatelly, during that "quantifiaction" of the uncountable world around us into finite information in a form of speach we loose some information, but by adding more and more categories we can describe anything we want any wanted accuracy.

Kurt Gödel theorem tells us that it's not possible to build complete model of the reality around us operating in theories that uses countable sets as basis. The idea of math is to find finite set or language based on countable number of axioms failed.

The good thing is that no one prohibits us to extend the language we use, to add new categories and to describe the world around us presizer with each new category added.

From that perspective all the arts: paintings, films, literature, martial arts are the way to add a new category into common knowledge. It's one brick in the wall of model of reality.

Thorough it's hustory humanity found lot's of ways to save and reproduce information and computers and internet is a major step that made possible precice copy at almost no cost.

In some sense nowdays internet has all the collective knowledge acceseble by humany. It's really hard to find something in the internet. Search engines, databases, social media and chats helps us to find and manage with information.

The problem is that it's designed for machines, not humans. All the services has different API's. People created different tools like business intellegence frameworks, algorithm like ML & AI to be able to process all the information around us, but mostly they focused on collective knowledge, when person has manually to put information into the system.

That's unnatural to use. In our heads we have a model of reality based on our own set of categories, our own personal expirience. Nowdays lot's of services stores our data but we need a local personal database that is complitely controlled by a person. In other worlds, it'll be really nice to have a one tool that stores all the information you've ever faces: from articles you read and films you've seen to bills.

Such a database with a fulltext search will significantly increase personal productivity. Compbining it with a possibility to share some of the data with other, maybe based on blockchain technology will significantly increase the progress.

From a technical perspective we need to design a database that can be integreated with every service you need and data to that database must be added almost automatically, without overheads for a person. The data has to be stored locally, and there should be a way to exchange it with other people and entities.

<a name="specification"></a>
## Specification

<a name="specification-brief-description"></a>
### Brief description

The idea is to design local personal database that will index all the information you deal with. For example you read an article and save it to database (maybe with comments). After that you will be able to search over that information just like Google serches in the internet or in Google Drive.
The system should help you to connect different information streams around you. For example you should be able to save you utility bills, checks and later to build charts showing your expences and maybe be find a correlation between them and your health.
In other words system can be described as universal storage of different data that a person has full control on. The system must be designed based on "human-first" principle, meaning that the system adapts to humans not vis a versa. It means that system must be customizible, interface should be self-explanational, system must be tolerant to human errors.  

<a name="specification-technical-requirements"></a>
### Technical requirements

1. Spec1: One-click information adding
2. Spec2: Systems stores and indexes all the added information
3. Spec3: Systems allows to store relationship between objects in a different form (analytically and manually)
4. Spec4: System must be crosspalform
5. Spec5: System must be able to data in a form of table, graph, chart on one screen, block texts editors
6. Spec6: User must be able to store all the data locally
7. Spec7: Systems must be able to communicate to each other. User must be able to control what information him shares with others.
8. Spec8: System must be extenseble and able to connect to different data sources.
9. Spec9: System must be able to join data from different sources
10. Spec10: System must work async
11. Spec11: System must have advanced collision resoultion capabilities

<a name="specification-design-requirements"></a>
### Design requirements

1. Dis1: Systems must be adapted to humans
2. Dis2: It must be convinient to use the system
3. Dis3: Several color themes
4. Dis4: Minimalistic interface
5. Dis5: System must have great internal documentation
6. Dis6: Internal documentation must be implemented on the system
7. Dis7: System must be responsible

<a name="observations"></a>
## Observations of the world around us

<a name="observations-applications"></a>
### Applications

- Competitive analysis
- Data mining
- Linkage analysis
- Knowledge network building
- Zettelkasten method
- Experiments analysis

<a name="observations-use-cases"></a>
### Use cases

- Trello & Spreadsheet integration
- Google disk files analysis
- Google Disk access management
- Analyzing competitors
- Finding decision-makers
- Scenario writing
- Personal photo & video archive

<a name="implementation"></a>
## Implementation

TODO: Describe software implementation

<a name="implementation-software-stack"></a>
### Stack

<a name="references"></a>
## References

1. [Ontology](https://en.wikipedia.org/wiki/Ontology)
2. [Category theory](https://en.wikipedia.org/wiki/Category_theory)
3. [Homotopy type theory](https://en.wikipedia.org/wiki/Homotopy_type_theory)
4. [Universal grammar](#https://en.wikipedia.org/wiki/Universal_grammar)

<a name="licence"></a>
## Licence

Licensed under [Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)
