---
title: Searching for citations
permalink: /searching/
---

### Searching for citations

#### Keywords

Enter the keywords for your search in the **<span style="color:blue">PLANNING</span>** section of colandr.

Terms can be entered alongside synonyms/alternative terms. Terms that have the same group assignment will be connected to each other with OR within a single set of parantheses. For example - for this set of keywords:

Terms related to marine habitats: ocean, sea, marine, coral reef, reef, beach

You may enter one of them as the term and the rest as synonyms
Term = ocean
Synonyms = sea,marine,coral reef,reef,beach
Group = marine habitats

**OR**

you may choose to enter them as separate terms, connecting only terms that are very similar
Term = coral reef
Synonym = reef
Group = marine habitat
All other terms would entered as separate terms with no synonyms and group = marine habitat

![Search terms](/images/searchterms.png)

#### Boolean queries

Colandr can help users structure boolean queries for searching.

Keywords with the same group are connected by OR. Groups of keywords are connected by AND.

Currently colandr does not have the capability to incorporate Boolean functions such as NOT and NEAR within its framework. We suggest that you 

#### Conducting search

Users can take the formatted Boolean search query and use to search publication databases. Remember to format the string as needed to include the appropriate field codes for each database.

> Due to subscription paywalls and copyright laws, colandr does not connect directly to citation databases such as Web of Science or MedLine to search for citations nor download citations. Users will need to use their own accounts to log in and search.

{% include alert.html type="success" title="Linking to other packages for searching" content="Colandr can help you format a boolean search query - however, it cannot help you conduct the searches themselves (this requires individual access to publication databases, etc...) or help you test whether your search query is efficient and comprehensive. Emerging applications of machine learning and text-mining may be able to help with this. You can visit the [colandr companion][] to trial a beta version of keyword search optimization that utilizes litsearchr." %}

[colandr companion]: https://scheng.shinyapps.io/colandr_stats/