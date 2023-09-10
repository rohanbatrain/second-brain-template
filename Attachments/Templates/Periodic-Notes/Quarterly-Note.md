---
tags: templates/quarterly-note [[<%tp.date.now("YYYY")%>]]
links: [[Quarterly-Reviews]]
---

# <% tp.file.title %>

[[<%tp.date.now("YYYY-[Q]Q", -90)%>]] <== [[<%tp.date.now("YYYY")%>]] ==> [[<%tp.date.now("YYYY-[Q]Q",+90)%>]]

## Summary

```dataview
table month-summary as Summary
from [[Monthly-Reviews]] AND [[<% tp.file.title %>]]
sort file.name asc
```

## OKR

### Focus Area 1 :

Objective:

* 

Key Result:

* 

I will accomplish this by:

* 

Related Projects:

* 


## Log
---
