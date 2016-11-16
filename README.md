# sub2call
Search the LC subject classification, retrieve call numbers

This project is an attempt to make Library of Congress call numbers more searchable/discoverable. Attached are files containing an array of values taken from the LC Classification Outline linking the classes/subclasses to their respective call numbers.  

The code is based on Jquery UI's autocomplete functionality (https://jqueryui.com/autocomplete/). Use the javascript file as an external array, or the HTML file with the basic code as a minimally internally styled page.   

Entries are taken directly from the LC Classification Outline, which is an incomplete though freely available listing of the classes and call numbers. 

A few minor additions have been made to this array, including a correlation of words containing diacritics (entries with diacritics are matched by those without), as well as ranges for subclasses that are overly general ('nursing specialties' are not listed in the LC outline, additions listed here). 

Future improvements may address eliminating overly redundant entries and/or their structure (use of the 'general' limiter occurs often) as well as terms for common/popular entries currently not listed ('Internet', common popular names). 

Feel free to add your own improvements to make LC classification more discoverable. 
