### REGEX Notes 


- What is it 

    - Regula Expression (REGEX) is as specific search pattern that can be used to easily match locate and manage text. 
- Uses of RegEx
    1. Input validation 
        the process of ensuring input complies with predefined application standards.
    2. String parsing 
        the process of pulling info from a file and turning it into a usable string by extracting the information needed from the file.
    3. Data scraping 
        the process of extracting data (usually from a web page)
    4. String manipulation 
        the process of taking a string and changing it via various methods to contain only the data needed

- Scenarions of retrieving pieces of text
    - Extracting phone numbers that start with certain digit
    - Extracting specific shades/tints of thread from a list of thread colors
    - Collectining all street names from a bulk text, even if they dont follow a specific pattern 
    - RegEx has a predefined expression to locate all the URLs in a strings

- Methods in UiPath that use RegEx 

## Matches
- Searches an input string for all occurrences and return all the sucessful matches 
- Out datatype: 
    - System.Collections.Generic.IEnumerable<System.TextRegularExpressions.Match>

    - Types of programs used in the Matches activity
        - \w matches with any word characters -  /W does the opposite
        - \d matches with any number character - \D does the opposite
        - [] matches with any characters written between brackets - [^] does the opposite
        - (|) allows you to match multiple characters such as (yes|no)
# IsMatch 
- Indicates whether the specified regualr expression finds a match in the specific input string.
# Replace
- Replace strings that match a regular expression patterns with a specified replacement string
- Output datypes: String
![img](<https://raw.githubusercontent.com/miketuskey/ReGex/afcc8eeb4c2fb39f7bc58e34480e376849dce080/SylvesterReplace1.jpg>)
![img](<https://raw.githubusercontent.com/miketuskey/ReGex/main/SylvesterOutput.jpg>)
