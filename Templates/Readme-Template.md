---
<<<<<<< HEAD
Date: 2021-12-28
Author: Jimmy Briggs <jimmy.briggs@jimbrig.com>
Tags: ["#Type/Readme"]
Alias: Work-Templates
---

# Work-Templates

*Contents*

```dataview
list from "Templates/Work-Templates" AND !#Type/Readme
```
=======
Date: "<% tp.date.now() %>"
Author: Jimmy Briggs <jimmy.briggs@jimbrig.com>
Tags:
  - "#Type/Readme"
Alias: "<% tp.file.folder() %>"
---

# \<% tp.file.folder() %>

*Contents*

````dataview
list from "<% tp.file.folder(true) %>" AND !#Type/Readme
````
>>>>>>> main

---

*Backlinks*

<<<<<<< HEAD
```dataview
list from [[Initiative-Template]] AND -"Changelog"
```
=======
````dataview
list from [[<% tp.file.title %>]] AND -"Changelog"
````
>>>>>>> main
