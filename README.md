# sub2call
Search the LC subject classification, retrieve call numbers.

This project is an attempt to make Library of Congress call numbers more searchable/discoverable. Attached are files containing an array of values taken from the LC Classification Outline linking the classes/subclasses to their respective call numbers.  

The code is based on Jquery UI's autocomplete functionality (https://jqueryui.com/autocomplete/). Use the javascript file ("master array") as an external source, or the HTML file with the basic code as an internally (un)styled page.   

Entries are taken directly from the LC Classification Outline (https://www.loc.gov/catdir/cpso/lcco/), which is an incomplete though freely available listing of the classes and call numbers. Those with a subscription to Classification Web have access to the full classification outline. 

Because LCCO is an incomplete listing, I've made a few minor additions to this array, including:
  - correlation of words containing diacritics (entries with diacritics are matched by those without)
  - ranges for subclasses that are overly general ('nursing specialties' is a good one and are not listed in the LC outline;  I have added some to this array). 
  - Common usage synonyms sparingly added, when felt necessary. 'Internet' strangely does not appear in LCCO, closest term is 'information superhighway'. I added it here within the TK and ZA classes. 

Future improvements may/should address eliminating overly redundant entries and/or their structure (use of the 'general' limiter occurs often) as well as terms for common/popular entries currently not listed ('Internet', common popular names). 

Also added is an HTML page for a reverse call number lookup, based on class. Search the general class (B, GV, QC) and retrieve the subject. This is a more general array, but it does demonstrate potential utility. 

Feel free to add your own improvements to make LC classification more discoverable or programmatically transferrable. Thanks! 
