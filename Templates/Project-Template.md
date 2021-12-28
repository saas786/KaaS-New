---
<<<<<<< HEAD
Date: 2021-12-28
=======
Date: "<% tp.date.now() %>"
>>>>>>> main
Author: Jimmy Briggs <jimmy.briggs@jimbrig.com>
Tags:
  - "#Type/Project"
  - "#Topic/PwC"
Alias: "<% tp.file.cursor() %>"
---

<<<<<<< HEAD
# Initiative-Template

- 🔗 - < add link to Todoist project here >
- 📁 - < add URI/path to project directory here >
=======
# \<% tp.file.title %>
>>>>>>> main

* 🔗 - \< add link to Todoist project here >
* 📁 - \< add URI/path to project directory here >

## Contents

<<<<<<< HEAD
```dataview
list from "Templates/Work-Templates" AND !#Type/Readme AND -"Changelog"
```
=======
````dataview
list from "<% tp.file.folder(true) %>" AND !#Type/Readme AND -"Changelog"
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
