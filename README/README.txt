# IAS log source notes
- DTS (XML) format is one of three options how to log IAS data. It's preferred by Microsoft and richest in information. 


# Add-on description
The purpose of Splunk TA add-on for MS IAS is to do both search and index-time parsing of MS IAS logs in DTS (XML) format.

## Index-time parsing
- strips <event> and </event> tags
- strips ' datatype="<number>"' attributes within XML tags to make final search-time parsing look cleaner

## Search-time parsing
- automatic XML parsing

## CIM normalization
none
