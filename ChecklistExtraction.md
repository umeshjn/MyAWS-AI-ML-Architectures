## Extracting the data from Checklists used by Auto Manufacturer

Company which manufactures products different variants of cars and has thousands of service engineers working on servicing. They have different service checklists(PDF versions) which are filled by these service engineers. This has been going on for years and they have all this information sitting in PDF files without adding any value to the business and its customers. 

Company has decided to scrape these files and pull out the information from the pdf files. Manually pulling out this information is going to take forver and very costly affair. Doing it through script is a possibility but there are 100s of different templates.

Most cost effective and faster way to do this is using AWS services specially Textract which is a very powerful service for pulling data from such forms. This does not need any scripting or customization for pulling the data out.

<br>

![](/images/AutoServiceChecklist.png)



<br>

Extracting and storing is just the start for what is possible. This data can be married with lot of other datasets about the cars and customers.

- Proactively identify the cars which might have problems based on the existing data.
- Identify the parts which are showing signs of early wear and tear due to lack of quality
- How many customers are not following the recommendations? Are they ending up with the troubled cars due to this?
- Are all recommendations provided good ones? 

So much more. 
