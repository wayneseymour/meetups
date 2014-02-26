### MongoDB and Schema Design

#### Embedding values

* arrays
 * arrays of docs, strings, numbers, etc
* embedded documents
 * embeds one, embedded in, embeds many

 **Makes schemas really flexible**

### One to Many, Many to Many
- one to many gen recommend
-- full info all at once

Note: max doc size is 16MB *scaling issue*

Note: Aggregation Framework -> results in a document

> No joins, arrays instead

> keep working set in mem, magnetism is always slow

schema versioning is just like rdbms's, but is easier!  :)

> embedding is like pre-join, since you plan on viewing this data together anyway

bson data format was designed to be fast

> referencing helps with scalability...you are just shoving it somewhere else

========================