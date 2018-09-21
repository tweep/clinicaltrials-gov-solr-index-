

### Notes on how to index the clinical trials gov server with SOLR 

The example below uses the SOLR XPathEntityProcessor 

1) fetch data 

    wget --no-check-certificate 'https://clinicaltrials.gov/show/NCT01397578?displayxml=true' -O NCT01397578.xml 

2) adjust schema.xml and xml-data-config.xml (which controls how XPathEntityProcessor is applied ) to 
  define what you want to index 

3) Adjust also the dir where all the xml files are which you like to index 

4) use data import handler to import  the data 



