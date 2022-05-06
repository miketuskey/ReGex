### REGGEX Notes 


- What is it 

    - Regula Expression (REGEX) is as specific search pattern that can be used to easily match locate and manage text. 
- Uses of RegEx
    1. Inout validation 
    2. String parsing 
    3. Data scraping 
    4. String manipulation 

- Scenarions of retrieving pieces of text
    - Extracting phone numbers that start with certain digit
    - Collectining all street names from a bulk text, even if they dont follow a specific pattern 
    - RegEx has a predefined expression to locate all the URLs in a strings

- Methods in UiPath that use RegEx 

## Mathces
- Searches an input string for all occurrences and return all the sucessful matches 
- Out datatype: 
    - System.Collections.Generic.IEnumerable<System.TextRegularExpressions.Match>
# IsMatch 
- Indicates whether the specified regualr expression finds a match in the specific input string.
# Replace
- Replace strings that match a regular expression patterns with a specified replacement string
- Outputdatypes: String

--

## About Replace 
- Replace is input string that replaces strings that matches a regular expression pattern with a specific replacment string. 

## Replace Properties
- Pattern- is the regular expression pattern being matched.
- Input- is the string that is being replaced.
- Regex Option- is a list of specified options for matching.
- Replacement- just replaces the string.



 


