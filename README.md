# TextMiningStCroixAvis
Material for the introduction to text mining workshop made for those interested in learning about digital methods and experience how coding can be used to work on larger bodies of text.

## Aim
The aim of this text mining workshop is to introduce newcomers to text mining and working with data. This is done by attendees working with the methods and material themselves. The material used in the workshop is text based data and metadata form the Danish newspaper St. Croix Avis from the 1878. This newspaper is used due to the content being relevant for danish history. The paper is written in English which allows for a broader body of attendees beyond danish speakers. We focus on the year 1878 to place the workshop in a histoical context, allowing the attendees to gather information about what news was covered and which keywords could be interesting during the time shortly before the end of European settlement of the island.

## Data
The dataset consists of newspapers from St. Croix more specifically the Danish newspaper "St. Croix Avis". Original prints of the newspaper have been collected and kept at the library back in the days. Throughout the years the number of newspapers collected have become so numerous that smarter and more space-efficient storage was needed. Older newspapers were therefore photographed and transfered to microfilm. In 2014 the microfilms was digitized both to further optimize storage and make the process of retrieving newspapers easier. The process of digitization also involved text recognition (called Optical Character Recognition; OCR) which made it possible to do free text searches through the newspapers. However OCR has ist challanges and pitfalls especially when the material that it is put to work on is digital renditions of photographed newspapers. OCR works very well on 'modern' characters and clear rendered documents but has some diffulties reading texts that have been through a number of renditions which can leave pieces of text unclear, this can result in OCR-mistakes where the text has not been recognised. 

![](https://github.com/TokeJoMu/imagework/blob/main/CroixForside.png)

The data is made available through an Application Programming Interface (API) which is a software that allows devices to share data. This particular API (http://labs.statsbiblioteket.dk/labsapi/api//api-docs?url=/labsapi/api/openapi.yaml) provides publicly available data and metadata from old newspapers at the Royal Libary's newspaper collection.

## Data processing
The data processing in our case text mining will be done with the statistical coding language, R. In order to save time on installation and so on this is done through the browser-based [RStudio Cloud](https://rstudio.cloud/). This runs R and RStudio in your browser and you will be up and running once you've signed up!

## Methods and approaches
The methods and approaches to text mining that we work with in this workshop is based on the tidytext-principle. In this principle each word of your target text-element will be put on its own row, while retaining all other meta-data. For more information and also as post-workshop inspiration see: [Tidy Text Mining with R](https://www.tidytextmining.com)
