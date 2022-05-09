### REGEX  

---

- What is it 

    - Regular Expression (REGEX) is as specific search pattern that can be used to easily match locate and manage text. 

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
    - Collectining all street names from a bulk text, even if they dont follow a specific pattern 
    - RegEx has a predefined expression to locate all the URLs in a strings

---

## Methods of Regex in UiPath

---

## Matches
- Searches an input string for all occurrences and return all the sucessful matches 
- Out datatype: 
    - System.Collections.Generic.IEnumerable<System.TextRegularExpressions.Match> 
- Matching can be as used to look up words, emails, url, digits, and other specific sets of data that you are looking for in a file. 

- Types of programs used in the Matches activity

    - \w matches with any word characters - /W does the opposite
    - \d matches with any number character - \D does the opposite
    - [] matches with any characters written between brackets - [^] does the opposite
    - (|) allows you to match multiple characters such as (yes|no)

- Cheat sheet for Regex Expression
- https://cheatography.com/davechild/cheat-sheets/regular-expressions/

---

# Is Match 
- Indicates whether the specified regualr expression finds a match in the specific input string.
- Is Match is an excellent tool for creating Boolean fuctions and testing string statements. 
---

# Replace
- Replace strings that match a regular expression patterns with a specified replacement string
- Outputdatypes: String
- Replace is input string that replaces strings that matches a regular expression pattern with a specific replacment string.

- Replace Properties 
    - Pattern- is the regular expression pattern being matched.
    - Input- is the string that is being replaced.
    - Regex Option- is a list of specified options for matching.
    - Replacement- replaces the string.

----

# Links 

-  https://docs.uipath.com/activities/docs/is-match
-  https://www.tutorialspoint.com/vb.net/vb.net_regular_expressions.htm
-  https://www.youtube.com/watch?v=1UD02PCgdGg
-  https://excelcult.com/how-to-use-regular-expressions-in-uipath/
