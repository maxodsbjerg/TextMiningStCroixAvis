# Text Mining St. Croix Avis
Material for the introduction to text mining workshop made for those interested in learning about digital methods and experience how coding can be used to work on larger bodies of text.

## Aim
The aim of this text mining workshop is to introduce absolute newcomers to text mining and working with data. This is done by attendees working with the methods and material themselves. The material used in the workshop is text based data and metadata form the newspaper St. Croix Avis from the 1878. The paper is written in English and Danish which allows for a broader body of attendees beyond danish speakers. We focus on the year 1878 to place the workshop in a histoical context, allowing the attendees to gather information about what news was covered and which keywords could be interesting during the time shortly before the end of European settlement of the island.

## Data
The dataset consists of newspapers from St. Croix more specifically the newspaper "St. Croix Avis". St. Croix was in 1878 a part of the Danish colonies Danish West Indies (today's US Virgin Islands). Due to the connection to Denmark in the period original prints of "St. Croix Avis" have been collected and kept at the Royal Danish Library.  
Throughout the years the number of newspapers collected have become so numerous that smarter and more space-efficient storage was needed. Older newspapers were therefore photographed and transfered to microfilm. In 2014 the microfilms were digitized both to further optimize storage and make the process of retrieving newspapers easier. The process of digitization also involved text recognition (called Optical Character Recognition; OCR) which made it possible to do free text searches through the newspapers. However OCR has it's challenges and pitfalls especially when the input material is digital renditions of photographed newspapers. OCR works very well on 'modern' characters and clear rendered documents but has some diffulties reading texts that have been through a number of renditions which can leave pieces of text unclear, this can result in OCR-mistakes where the text has not been recognised. 

<img src="https://raw.githubusercontent.com/maxodsbjerg/TextMiningStCroixAvis/main/CroixAvisFrontPage.png" alt="Front page of St. Croix Avis" width="600"/>


The data is made available through an Application Programming Interface (API) which is a software that allows devices to share data. This particular [API](http://labs.statsbiblioteket.dk/labsapi/api//api-docs?url=/labsapi/api/openapi.yaml) provides publicly available data and metadata from newspapers older than 140 years at the Royal Libary's newspaper collection.

## Data processing
The data processing in our case text mining will be done with the statistical coding language, R. In order to save time on installation this is done through the browser-based [RStudio Cloud](https://rstudio.cloud/). This runs R and RStudio in your browser and you will be up and running once you've signed up!

The workshop is centered around the file "Workbook.Rmd", which is a notebook which both runs R-code and can have explaining text and pictures. In "Workbook.Rmd" all the R-code is missing and during the workshop the instructor will live code and the participants will repeat the code on their own computers. The file "CompletedWorkbook.Rmd" is the exact same document, but with all the R-code already there. 

## Methods and approaches
The methods and approaches to text mining used in this workshop is based on the tidytext-principle. In this principle each word of your target text-element will be put on its own row, while retaining all other meta-data. For more information and also as post-workshop inspiration see: [Tidy Text Mining with R](https://www.tidytextmining.com). This workshop ows alot to this great book and is a combination of the chapters 1 and 3.
