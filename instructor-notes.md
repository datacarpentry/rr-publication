# Publication lesson
Materials related to publication of research outputs (data, code, workflows, etc)

## Lesson Objectives

The goals of this lesson is to introduce what kinds of products should and can be shared, published and archived, who they need to be available for, the types of licenses should be used and where and how to publish products. This lesson comes from the perspective of "... so you're getting ready to publish your paper."

Participants will be able to:
- Understand the why, what, when, where, how and with whom aspects of research product publication
- Understand the differences between sharing, publishing  and archiving products
- Identify products that should or can be shared, published or archived
- Understand what copyright licenses are and what different ones mean for distribution and reuse
- Be aware of some of the repositories where products can be published
- Understand about and be able to create persistent identifiers for products, so that you more easily can track and get credit for your work
- Understand that there are funder or journal requirements for deposition
- Create READMEs to document information about the product
- Understand the importance of including metadata with data


## Notes

Section 0: Go through the slides with the below notes and overview on the slides.

Introduction:
As we tell a story with our data and analysis (our paper), we want to be able to point to the elements that make up the paper so we and others know exactly what we did. What data, scripts and other elements should we keep and where should we put them?

Points to make in this lesson

* Published need not mean archived: availability and access for
  perpetuity.
* Published need not mean easily citable, and easily trackable for
    impact: acquire persistent identifier that is broadly supported in
    scholarly communication.
* Meeting funder and journal requirements. What are journals and funding agencies asking for?
* Who else can we make the products available for and what do we need to do? Collaborators, peer reviewers, journal editors, broad scientific community, or generally the public
* Are the published products reusable? Are they in a format and sufficiently documented that others can build on them?
* Is it ready for public consumption?
  * Are things eligible for copyright protection properly licensed for reuse
 (and why does this matter)?
* Is there enough information that makes it easy for prospective reusers to give credit in the desired form?
* Is there an appropriate amount of documentation? READMEs etc.
* Are there sufficient metadata for each component?


Section 1:  
The lesson starts with "so you're getting ready to publish the paper based on the data and analyses in this workshop. What needs to be published and archived so other people and the you of 6 months from now, can recreate the work?"

Go through an exercise with the participants.
**Exercise:**
  * Catalog the things you have from the workshop**
  * where do they currently live?
  * what needs to be published? what needs to be archived?
  * how many are already published/archived?

**Exercise responses:**
* From the workshop, we have
- gapminder data
- R script for analyzing the data
- output of the analysis from the R script
- intermediate analyses
- analysis results from approaches we decided not to take
- notes on what we did
- a writeup (paper) of our conclusions of the analysis

What do we need to keep and what do we do with them?

One way to figure this out is to run through the analysis and figure creation in your paper. Note the products and notes you needed to re-create the analysis. Make that available.

- don't need to publish the raw data because it's already publicly available. If it weren't we would need to publish it along with the metadata that describes how the data was collected and about the measured variables.
- need to publish the code - the code we used to produce the results in the paper. You can point to it on github, but you should make a release for the version used in the paper, or publish that code somewhere
- metadata - this is the information that describes how you collected your data or things like the units in your columns. Without this information your data is often useless
- notes on any data transformation or clean up steps
- don't need to publish intermediate results, but this is at your discretion. If they were compute or time-intensive to generate, you might want to provide them
- code for analysis strategies you didn't take. You don't need to make this available, but if  you were using something like github for version control, people can look through history to see what you tried if they're interested
- write up of the work: the scientific conclusions of the analysis need to be published. This can be seen as the core object and all the supporting materials need to be published with it.
- a README file that describes the data, things like where and when it was collected, special collection details and information on how to run the code on the data, including parameters used if there were choices

Completeness is a judgment call: which parts are needed to understand, judge, and recreate the results reported in the paper. Also consider, what are the requirements of the funding agency or the journal?

Next section of slides goes through **now that we know what needs to be published/archived, where do we put it, and what are the considerations?**

Discussion at the end. Some people have or have heard of concerns around publishing data and code. These can be philosophical or practical because of implementation challenges. Leave some time in the lesson to discuss these issues and people's concerns.

**Discussion: What are some of the challenges of publishing research products? What are some of the concerns that people have?**





[@tnabtaf]: http://github.com/tnabtaf
[@kcranston]: http://github.com/kcranston
[@hlapp]: http://github.com/hlapp
