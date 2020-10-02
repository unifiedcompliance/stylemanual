# Manual of Style API calls

The Unified Compliance Framework team have developed Application Programming Interface \(API\) calls to aid, and standardize, portions of this Manual of Style. These API calls can be found online HERE. We will define their properties and use herein.

## naming-standard

Given a term, this endpoint processes that term and suggests the standard way it should be entered into the UCF system according to a suite of rules in the ruleset. A number from 1-8 indicates which ruleset is to be applied: 

### naming Rule 1

Sentence case, plural, allow acronyms, allow lists: We have found that the following rules apply to UNSPSC Asset Categories through Types.

### naming Rule 2

Title case, plural, allow acronyms, allow lists: We have found that the following rules apply to UNSPSC Asset Segments.

### naming Rule 3

Title case, singular, allow acronyms: We have found that the following rules apply to UNSPSC Products, Services, and Product Versions. Note that there are no spell checks for these terms as sometimes non-standard spelling in product and service names is undertaken by the product or service vendor on purpose.

### naming Rule 4

Lower case, singular, present tense, disallow acronyms: These rules are to be used for common verbs, nouns, adjectives, etc. Note that we are replacing all special characters with ASCII values \(if at all possible\) to aid the user in searching for these terms without having to learn special characters such as À or Æ.

### naming Rule 5

Lower case URL, disallow acronyms: These rules are to be used when entering URLs. Because URLs can be about anything, there are no rules for lemmatization or spelling.

### naming Rule 6

CPE names: These are specialized names that follow the Common Product Enumeration guide-lines set by the US’ National Institute of Standards and Technology.

### naming Rule 7

Roles, Group Names, and Titles: When entering an individual’s title, the name of a group, or a role that can be assigned to someone, follow these rules.

## lemma

This endpoint returns the base lemma for the entered term or phrase. Lemmatizing just the last word in a phrase is also possible.

## grammar

This endpoint will check the grammar and spelling of text and return suggestions of improvements or fixes.

