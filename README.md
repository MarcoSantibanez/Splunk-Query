# Splunk-Query
As a cybersecurity analyst I had to use Splunk Cloud to investigate an incident. 

Tools used:   *Splunk Cloud*

First I started with a basic search with the ingested data using *index=main*:

![Screenshot 2023-06-29 141058](https://github.com/MarcoSantibanez/Splunk-Query/assets/138132151/4c9e4f96-a853-4165-bc87-9da481394200)


Then I narrowed my search using *index=main host=mailsv*: 

![Screenshot 2023-06-29 141239](https://github.com/MarcoSantibanez/Splunk-Query/assets/138132151/f39871e4-4130-4dc9-b788-e48e05a353a5)

Lastly I further expanded my search using *index=main host=mailsv fail** *root*:

![Screenshot 2023-06-29 141339](https://github.com/MarcoSantibanez/Splunk-Query/assets/138132151/3f30e880-d9da-4999-b8c6-7c6b8894cf03)


Summary: I was able to perform a basic search in Splunk Cloud using ingested data. 



