```dataview
List author as Author, ("![|100](" + cover + ")") as Cover, category
From #Book 
Where contains(status, "To Read")
```