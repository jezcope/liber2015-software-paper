---
title: "The missing piece: saving software for reproducible research"
author:
- Jez Cope, University of Sheffield
- Contributors! Add your names here!
---

## Abstract ##

<!-- NB. This is currently the abstract as submitted to the conference. -->

Reproducibility has always been a central pillar of scientific research. The journal article is the gold standard in enabling this, describing the motivation, methods, results and conclusions of a piece of work. It is generally impossible to include the full underlying data within a paper, so authors instead make do with summaries, statistics and carefully-selected subsets. This approach makes it difficult to validate the conclusions of the paper, and to overcome this shortcoming there is increasing pressure on researchers to improve access to their underlying datasets.

However, the data is only half of the story. The calculations required to generate or analyse it are often too complex to give more than a general sketch in the methods section. When another researcher tries to reproduce the analysis, they quickly discover that there are many implementation details and edge cases left out of the description. The inevitable conclusion is that it is impossible to reproduce and validate another's results without also having access to their software.

Software poses new challenges for all involved with its curation and preservation. It is not sufficient to preserve only the source code: the ability to reproduce a given set of results also depends on specific versions of language tools, libraries and a full stack of infrastructure right down to the hardware. The usefulness of the code also relies on the skill of the programmer in documenting and structuring it in a logical, comprehensible fashion, for which training needs to be provided by an experienced professional. Research software is continually evolving, so it is important to link each published result to the specific iteration of the software that produced it.

This paper will argue that the bespoke software written for research should be recognised as an irreplaceable part of the scholarly record, and as such needs management, curation and preservation alongside the data it is created to generate or analyse. Initiatives such as Software Carpentry (<http://software-carpentry.org/>) and groups such as the Software Sustainability Institute (<http://software.ac.uk/>) are making great progress in raising awareness of these issues and providing training. Research libraries, with their traditional responsibility for managing and preserving the scholarly "inputs" and "outputs" of their institution, have an important part to play in developing there institutions' "software collection".

## Introduction ##

***NOTE: My use of language isn't particularly "academic" - is that a problem?***

***TODO: Choose between first- and third- person and stick to it!***

## What is research software? ##

***NOTE: maybe some of this material should come after "Why preserve software?" - easier to define the scope of research software after specifying the purpose of preserving it***

"Research software" is surprisingly difficult to define.
***TODO: cite existing definitions of research software***
All modern researchers make use of software in their work,
whether they are developing complex computational models from scratch
or simply writing papers and preparing lecture material.
Not all of this software can reasonably be considered research software *per se*;
a word processor, for example,
is a very general tool whose use is not restricted to research.
It is certainly not possible to define research software
by an exhaustive list.
Where would you start?

However, it is possible to make a functional definition based on
how the software is made
or how the software is used.
In other words research software could be either:

1. Software *developed by researchers*; or
2. Software *used for research*

### Software developed by researchers ###

Research has been associated with computers as long as there have been computers:
the earliest computers
(such as … ***TODO: ENIAC?***)
were developed by and for academic researchers.
The technologies that became the modern internet,
email and the world wide web,
were both developed as tools for scholarly communication.

***TODO: more detail about early computers?***

### Software used for research ###

Commodity software,
not designed specifically for research,
is also commonly used by researchers.
This ranges from
popular office software used by most of the world's IT-literate population
to specialised packages with both industrial and academic applications.

## Why preserve and share software? ##

The foundation of scholarly research and the scientific method
is the scholarly record.
[Someone] ***TODO: who the hell was it? Newton? Einstein?*** famously remarked:

> "If I have seen far, it is by standing on the shoulders of giants"

Libraries and archives are the guardians of the scholarly record
and it is tempting to treat the worth of that guardianship as self-evident.
It is not sufficient simply to preserve knowledge however.
Knowledge that is preserved but never referred to is worse than useless:
it costs money simply to maintain it in a usable condition.
So why do it? There are three complementary reasons:

1. To ensure a contribution to world knowledge
2. To ensure transparency and demonstrate the integrity of the scholarly record
3. To save time, effort and money

The primary aim of academic research is to increase human quality of life
by constantly expanding the body of human knowledge.

The integrity of the scholarly record is based on trust:
new discoveries are based on chains of insight going back centuries
and each link in that chain must be absolutely trustworthy
or all subsequent work building on it could be invalidated.
Before the development of computational methods
and the explosion in data-collecting capacity generally,
it was possible to include the whole argument supporting a new conclusion
in the space of a single publication.
A relatively high-level description of the procedure carried out by the humans performing the analysis
was sufficient to enable reproduction and verification of the result.

When the method is computational however,
that high-level description is no longer enough.
Computers obey the instructions given precisely,
and thus required very precise instructions.
In turning a high-level description of an algorithm
into an executable implementation
there are many design decisions that can be made
which will radically effect the outcome.

***TODO: include Diederich Stapel example here?***



## Why libraries? ##

***NOTE: this whole document repeatedly refers to "libraries" and "librarians" but also implicitly includes archives and museums - perhaps "memory institutions" would be better?***

Although the nature of the modern academic library is changing rapidly
***TODO: citation -  there must be a good reference for this! ***
its underlying function has not changed in centuries:
librarians facilitate access to and keep safe
the scholarly "inputs" and "outputs" of the university.
Those inputs and outputs are no longer restricted to printed words on paper,
but now include, amongst other things:

- electronic versions of traditional print materials, such as books and journals;
- grey literature, such as project reports and policy papers;
- new media, such as blog posts;
- presentations and posters;
- datasets;
- and, of course, software.

Although we have more experience of,
and historically a closer association with,
those items near the top of this list,
the information management skills required transfer well to other forms of information.
Libraries and archives therefore have the specialist skills

## What does software preservation look like? ##

***TODO: diagram of software components from presentation***

***TODO: this section could use particular attention from LP***

## What can librarians do about it? ##

1. Treat software as a first-class citizen of the library
2. Work with those helping researchers to write better software(/research software engineers)
3. Learn more about how computers work and software is written

Software, as with most technology,
is usually seen as the sole preserve of the university IT department.
Many librarians feel uncomfortable even thinking about software
except where its use relates to their core expertise as managers of information,
and this can sometimes be exacerbated by siloing of support departments
and a desire not to tread on anyone's toes.

However, as technology has become more ubiquitous
it has become necessary for IT to work in partnership
with other departments who have complementary skill-sets.
As the institution's memory,
the university library is the natural guardian of research software as a scholarly output,
and it is a logical extension to apply that to the realm of software.
Where the IT department is ideally placed
to provide the infrastructure to run software
and the support in its use,
so the library is ideally placed to give that software
its proper place in the scholarly record.
It is therefore the librarian's right and privilege
to be involved in the preservation of software.

As librarians, it is important for us to be confident in our own expertise
and to proactively work in partnership with both researchers and IT colleagues
to apply that expertise to research software.

***TODO: section about working with RSE - MC to write?***

Learning a little bit of the language of computers has other benefits too.
It will give you new ways of understanding and solving problems,
and even when you don't feel comfortable implementing the solution yourself,
you will be better equipped to explain it clearly to your systems librarian or software developer.

## Conclusions ##

### Outstanding issues ###

### The future ###

## References ##
