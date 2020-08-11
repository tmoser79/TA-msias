# Description
The purpose of Splunk TA add-on for MS IAS is to do both search and index-time parsing of MS IAS logs in DTS (XML) format.

## Index-time parsing
- strips <event> and </event> tags
- strips ' datatype="<number>"' attributes within XML tags to make 

to make final search-time parsing look cleaner


## Search-time parsing
- automatic XML parsing
 
