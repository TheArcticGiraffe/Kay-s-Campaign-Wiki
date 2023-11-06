
# Lore Questions
```dataview
TASK
WHERE tasktype = "question" 
GROUP BY location
```
AND location = [[The Gate]]

span.dataview.inline-field { display: none }
# Testing
```dataview
TASK
WHERE tasktype = "task"
GROUP BY link
```