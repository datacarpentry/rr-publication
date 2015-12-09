# Publication lesson
Materials related to publication of research outputs (data, code, workflows, etc)

## Lesson Objectives

The goals of this lesson is to introduce what kinds of products should be published, what types of licenses should be used and where and how to publish them. This lesson comes from the perspective of "... so you're getting ready to publish your paper."

Participants will be able to:
- understand the differences between sharing, publishing  and archiving products
- Identify products that should or can be published
- What copyright licenses are and what different ones mean for distribution and reuse
- identify the differences between publishing and archiving products
- what are repositories where prodcuts can be published
- persistent identifiers for products, so that you more easily can track and get credit for your work
- checking that funder or journal requirements are met for deposition
- create READMEs to document information about the product
- understand the importance of including metadata with data
- work with a representative repository

## Notes

Section 1:  
The lesson starts with "so you're getting ready to publish the paper based on the data and analyses in this workshop. What needs to be published and archived so other people and the you of 6 months from now, can recreate the work?"

Go through an exercise with the participants.
**Exercise:**
  * Catalog the things you have from the workshop**
  * where do they currently live?
  * what needs to be published?
  * how many are already published?

**Exercise responses:**
* From the workshop, we have
- gapminder data
- R script for analyzing the data
- output of the analysis from the R script
- a writeup (paper) of our conclusions of the analysis

- Gapminder data lives on github already
- R script lives in github repository
- output of the analysis lives on the local computer

The question then of what needs to be published is, "what needs to be available to be able to recreate the work?"

- Gapminder data already available: needed for reproducing the work
- R script is available on github: needed for reproducing the work
- output of analysis script is on local computer: doesn't need to be published, because it can be created from the initial data and the script. If it was particularly computationally intensive to generate, you might want to share or publish it though.
- metadata about how the data was collected and information like units things are measured in or what text codes mean
- write up of the work: the scientific conclusions of the analysis need to be published. This can be seen as the core object and all the supporting materials need to be published with it.
- a README file that describes the data, things like where and when it was collected, special collection details and information on how to run the code on the data.

 **Maybe a diagram with the paper in the middle and the data and scripts linking to it**


**Now that we know what needs to be published, where do we
put it, and what are the considerations?**


  * Published need not mean archived: availability and access for
    perpetuity.
  * Published need not mean easily citable, and easily trackable for
    impact: acquire persistent identifier that is broadly supported in
    scholarly communication.
  * Completeness is a judgment call: which parts are needed to
    understand, judge, and recreate the results reported in the paper.
  * Are the journal's or funder's requirements for sharing of research
    products met?
  * Are the published products reusable? Are they in a format and
    sufficiently documented that others can build on them?
* For whom does this need to happen?
  * Collaborators
  * Peer reviewers, journal editors
  * Broad scientific community, or generally the public
* Is it ready for public consumption?
  * Are things eligible for copyright protection properly licensed for reuse
    (and why does this matter)?
  * Is there enough information that makes it easy for prospective
    reusers to give credit in the desired form?
  * Is there an appropriate amount of documentation? READMEs etc.
  * Are there sufficient metadata for each component?

[@tnabtaf]: http://github.com/tnabtaf
[@kcranston]: http://github.com/kcranston
[@hlapp]: http://github.com/hlapp
