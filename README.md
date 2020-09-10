# GBBAT 
Initially, I planned for us to write a practice paper for the Data Science Journal on our creation of GBBAT. However, since our transition to BigQuery, I believe that we should broaden the scope of our writing. Now, instead of an essay that provides *some insights*, we can discuss on research on the development and operation of GBBAT.

## Data Science Journal scope
> publishing papers on the management, dissemination, use and reuse of research data and databases across all research domains, including science, technology, the humanities and the arts. The scope of the journal includes descriptions of data systems, their implementations and their publication, applications, infrastructures, software, legal, reproducibility and transparency issues, the availability and usability of complex datasets, and with a particular focus on the principles, policies and practices for open data.

## Research Paper
> Research articles must describe the outcomes and application of unpublished original research. These should make a substantial contribution to knowledge and understanding in the subject matter and should be supported by relevant figures and tabulated data. Research articles should be no more than 8,000 words in length. Data and software supporting the research should be formally cited and available through a trusted repository.
## Suggested Outline for GBBAT Research

1. Introduction
> - Motivation
> - Introduce GBBAT 
> - Why this is an appropriate time
> - how we did it created GBBAT
> - what we found during our creation, prototype, BigQuery transition
> - How does it relate to other data products and research on these types of data products/AWS/GCP/costs/storage
2. GDELT database
> - Overveiw of data and our subset
> - Relation of tables
> - Persistence discussion
3. Conceptualization of GBBAT Data Product
> - Data problem and GBBAT as a solution
> -  China focus: Market of Users and Competition for Data Opportunities
> - Conceptual Framework of GBBAT, i.e. value-added, analytical issues, 
4. GBBAT Prototype
> - Defining the scope of the MVP/Prototype
> - Choice of AWS and MySQL
> - Choice of query constraints: the forced two-stage choice
> - Prototype Size/dimension and analytical potential for a user
> - Limitations discovered in prototype
> - Scaling Up: Anticipated size and dimension
5. Transition of GBBAT to Google BigQuery
> - Motivation
> - Benefits and Disadvantages
> - Comparative Cost/computing power trade-off between AWS/MySQL and BigQuery
6. Conclusion

## Figures/graphics

1. Visualization of three tables' relations within GDELT
2. China and sources percentage of GDELT tables
3. Predicted accumulation of usable data tables over time and as sources are added
4. GUI of user access
5. Comparison of computing time and cost from prototype to predicted size of final versions between AWS/MySQL and BigQuery.

# Other resources
## DSJ Practice Paper
The editor Mark Parsons suggested that the following makes a good practice paper.

>  A useful practice paper needs to say a bit more than a description of the event, tool, or practice. It should provide some insight or lessons learned. What is the message we should take from the experience? Are there clear demonstrated design principles that can be reapplied elsewhere? Are there roadblocks or bottlenecks that others might avoid? Are there suggested community or work practices that can make things smoother?

The Data Science Journal describes practice papers as: 

> Practice papers should report upon or critique a specific "happening" such as a release of a major study or other notable occurrence related to the journal focus. Authors interested in submitting a practice paper should discuss the content with the editor before submitting a manuscript. Practice papers should describe the finished outputs of a project, or the procedures in operation in an established data system. Practice papers should be no longer than 3,000 words in length.

## Latex
We write the article in Latex, `gbbat_manuscript.tex`

Our bibliography will be compiled within Mendeley. When we add new sources to Mendeley, we need to export a new .bib file
into our repo to replace the current bibliography file (`gbbat_references.bib`). 