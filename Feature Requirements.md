Original Author: Adam Conway
License: Released under Creative Commons Attribution 4.0 International



**Notes for reader** - The intention of this document is to be a more modern and lightweight version of the MRD and PRD that fits better into agile-ish processes.  Regardless of development process, Product Managers still sometimes need a good requirements document.  This document is an attempt to provide a template for use by PM orgs who sometimes need a requirements document. 

The biggest difference between this document and a classic document is that it emphasizes the feature description over requirements and has the requirements take on the role of success criteria.  The intention of this is to reduce the requirements section and create a shorter, more readable document.  This requirements document's audience is engineering.  
 
This document is only a guideline.

**Note for people who dont like this document** - Documentation process within an organization is often a reflection that particular organization's expectations.  So if it doesnt fit your process, fork it. 

**Note for people who prefer PowerPoint to write requirements** - I understand the allure of PowerPoint, one can merge text and pictures with ease, which frankly is unmatched in any other application, however, 

##Overview
This overview should, in no more than a few sentances, provide the reader with an overview of the product/feature and why we are building it.  A reader should be able to read this overview and know what the document is.  This is useful, because often people will have to sort through several requirments documents to find what they are looking for.  So do the future a favor and write a good Overview. 

###Links to other Relevant docs
Provide links to other relevant requirments or documents.  If you are using a document management system that doesn't support permanant links, then fix that part first.

## Feature Description
In my opinion this is the most important section of a requirements document.  This is your opportunity to describe what you expect out of the completed feature...  Except where not possible, this should be told from a users perspective using use-cases.  This section should include mockups and/or architectural diagrams if possible.
 
## Market Overview and Feature Justificaiton
It is important to explain why we are doing features, this section can be just a few sentances or longer for more complex features

## Requirements
This should be viewed as success criteria not as a description of the feature via requirments (which is the old school way of writing requirements, agile adherent's will mock you for writing features via requirements, and that should be avoided).  Things to think about in requirements are:

*  **Performance** - How well a feature performs, if it is a website, responsiveness is important, wheras with a system it might be throughput.  
*  **Usability** - How does the Product Manager expect the product to be used, and what effort is required for usability
*  **Configurability** - What kind of configuration options are expected, and what sorts of things are expected to be automatic.
*  **Compatibility** - This is an oft forgotten section of a requirements document.  This is compatiblity with different products within the company (e.g. this feature will be supported on Cybertron 1000 and 2000 but not 3000) or other platform support (e.g. this feature will be supported on OSX and Windows, but not Linux) 

##Design Considerations (Optional)
The classic school of thought is that PMs write only requirements and are barred from designing the product or being involved in the design... for lots of reasons this is counter productive (e.g. PMs, instead, writing extensive requirements such that the product can only be designed one way).  Rather it is my preference that the PM has a safe place to give their design opinion in the requirements doc.      

