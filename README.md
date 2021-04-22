> ####  `thinking regularly, thinking universally, thinking mathematically`

# List of Patterns 🎇 'Pattern-Collector'      
The* ['awesome List'](https://github.com/sindresorhus/awesome#contents) of Patterns        
\*_(there seems to be no other repo yet! So Please edit this draft  wildy 🎉 (Spreadsheet & Readme))_ 

Patterns make bite-sized tools/co-work 🍒🍿🍟🤏 ( Searching such list (,once well filled,) you will already have pre-defined the specific regular scope of your goal (copying a specific pattern. That can be more efficient/versatile than searching Stack Overflow Answers or node.js NPM's. Just like a tweet has a higher density per word than an article.)

## 1. **Reg**ular **Ex**pressions(=Search Patterns=Data format definitions.) 
Regex are most common & most efficient to type. (Despite they are one of the oldest dicsiplines in programming to make sense of data, convert it, clean it or spell-check it. 
https://en.wikipedia.org/wiki/Regular_expression)   
| Common Data Formats² | **pattern match** | replacement | _comment/justify_ | _raw³_ | _extra context/precision_ |
| --: | :-: | :--| --: | --: | --: |
|ISBN |||
|Youtube Video ID |`[^\w-]([\w-]{11})[^\w-]`| $1 | 11char base64 is almost unique| | `(?:https?://\|//)?(?:www\.\|m\.)?youtu/?be(?:\.com)?/(?:embed/\|v/\|watch\/?\?[&\w=]{,128}v=([\w-]{11})[^\w-]`| 
| **Hashes, Public Keys, Signatures** | **pattern match** |  |
| MD6 |||
| SHA256, Bitcoin, ... |||
| **Convert** | **pattern match** | **replacement** |
|MarkDown links to HTML links | `\[([^\]]*)\]\(([^\)]*)\)`|`<a href="$2">$1</a>`|
|**this table**2Javascript |\\|\`([^\`]\*)\`\\\|\`([^\`]\*)\`\\||`replaceAll(/$1/g, "$2").replaceAll("\\|","\|")`| 
|Javascript 2 Python | _..(..)..(..)..(..)..(..).._|_$9$7$2$8$4$3_|

*² date, postal code, formal greeting, formal __, ...* <br> _³ matching typos too, as long as that's still unique / unique enough_

[**Full List of 1000s**](https://github.com/code4charity/The-Regex-Collector--Queries--Patterns/blob/main/README.md#all-regex)

## 1.1 Pre-processing Patterns 
A List of Patterns / Regex can be analyzed for similarities and thus be combined in a preprocessing step. i.e. Preprocessing might Reduce Input data by 90% already in half the time. 

## 1.2 Automatic pattern generation

## 2. Contextual & Semantic patterns 
#### word-lists, topics, frequencies, thesaurus, antonyms,  semantic dictionaries, psychologic & sentiment dictionaries
wordnet, framenet, google ngrams, google trends, ....
#### Google Search: 
~synonyms a|b AROUND(3) c|d  -e|f|g|h|i|j|k|l|m|n|o|p|q|r|s|t|u|v|w|x|y|z    
https://ahrefs.com/blog/google-advanced-search-operators/
#### Human Grammar & Natural language processing (NLP):  
https://github.com/edobashira/speech-language-processing#readme

## 3. Structured Data. Querying Public Databases & the internet. SPARQL, SQL, NoSQL
#### Semantic web
#### WikiData
#### AWS public databases

## 4. Merging the above "1.-3."
### vs 5. Human work VS machine learning models

----

# All Regex  
## https://docs.google.com/spreadsheets/d/1EjeZ2RtNpM_mANdO1VPXmZmbIb5vANUXodPBFtdg3zU/edit
- Others Lists  // potential Sources: ___ , ___ , ___ , ____ ,____ , ( not a list but 1 repo per regex: https://github.com/regexhq )
- Compare:  https://www.mulesoft.com/exchange/?type=connector&view=list   (>10000 'enterprise converts')

| name | pattern | replace | language |
| --: | :-: | :--|  --: |
| | | | regex |
| | | | google | 
| | | | css |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |



