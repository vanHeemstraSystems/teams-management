# 300 - Teams Calendar Management

In Microsft Teams create a Calendar Event inside the Calendar specific to a Team (e.g. [ART] [Department] [Team Name] ).

Name of the Event: Sprint YYQ##.[SprintNr] - [ART] [Department] [Team Name]

Start Day: First Day of the Sprint

Last Day: Last Day of the Sprint

Recurring event: Monday, Tuesday, Wednesday, Thursday, Friday

All Day event.

Description:

```
Team Name: [ART] [Department] [Team Name]

Product Owner: [Product Owner Name]

Scrum Master: [Scrum Master Name]

Engineers:
  - [Engineer Name]
  - [Engineer Name]
  - [Engineer Name]

Products:
  - [Product Name]
  - [Product Name]

References: [Any links to references to the team or its documentation or point-of-contact or Scrum or Kanban Board, or link to their Teams Channel]

PI YYQ##.[SprintNr]

  - Theme: [Theme]

      - Category:
           - Sub category: (Un)committed, expected in Sprint YYQ##.[SprintNr] ([Link to Feature/Issue/Bug Nr])
           - Sub category: (Un)committed, expected in Sprint YYQ##.[SprintNr] ([Link to Feature/Issue/Bug Nr])

      - Category:
           - Sub category: (Un)committed, expected in Sprint YYQ##.[SprintNr] ([Link to Feature/Issue/Bug Nr])
```

Save the new event, it should show in MS Teams Calendar (provided you have the Team's Calendar visible).

The information about the PI should match what is presented in the [PI](https://github.com/vanHeemstraSystems/product-increment-planning-and-execution-management) report out, created at the [Tactical Planning](https://github.com/vanHeemstraSystems/tactical-planning-management) within the Agile Release Train (ART):

<table>
<th colspan="8">PI YYQ##.[SprintNr] - PIPE report out </th><tr/>
<td>Confidence vote</td><td>##/5</td><td colspan="6"></td><tr/>
<td>Strategic Objective</td><td>PI Objective</td><td colspan="5">Committment</td><td>Risk, Dependencies, Remarks</td><tr/>
<td></td><td></td><td>ART</td><td>Team A</td><td>Team B</td><td>Team C</td><td>Expected in Sprint</td><td></td><tr/>
<td>Theme: ABC</td><td colspan="7"></td><tr/>
<td>Category Description</td><td>Sub-category Description</td><td>(UN)COMMITTED/UNPLANNED</td><td>blank/blue/green/red</td><td>blank/blue/green/red</td><td>blank/blue/green/red</td><td>YYQ##.[SprintNr]</td><td>[Risk, Dependencies, Remarks]</td><tr/>  
<td></td><td>Sub-category Description</td><td>(UN)COMMITTED/UNPLANNED</td><td>blank/blue/green/red</td><td>blank/blue/green/red</td><td>blank/blue/green/red</td><td>YYQ##.[SprintNr]</td><td>[Risk, Dependencies, Remarks]</td><tr/>
<td>Category Description</td><td>Sub-category Description</td><td>(UN)COMMITTED/UNPLANNED</td><td>blank/blue/green/red</td><td>blank/blue/green/red</td><td>blank/blue/green/red</td><td>YYQ##.[SprintNr]</td><td>[Risk, Dependencies, Remarks]</td><tr/>  
<td></td><td>Sub-category Description</td><td>(UN)COMMITTED/UNPLANNED</td><td>blank/blue/green/red</td><td>blank/blue/green/red</td><td>blank/blue/green/red</td><td>YYQ##.[SprintNr]</td><td>[Risk, Dependencies, Remarks]</td><tr/>    
<td>Theme: DEF</td><td colspan="7"></td><tr/>
<td>Category Description</td><td>Sub-category Description</td><td>(UN)COMMITTED/UNPLANNED</td><td>blank/blue/green/red</td><td>blank/blue/green/red</td><td>blank/blue/green/red</td><td>YYQ##.[SprintNr]</td><td>[Risk, Dependencies, Remarks]</td><tr/>  
<td></td><td>Sub-category Description</td><td>(UN)COMMITTED/UNPLANNED</td><td>blank/blue/green/red</td><td>blank/blue/green/red</td><td>blank/blue/green/red</td><td>YYQ##.[SprintNr]</td><td>[Risk, Dependencies, Remarks]</td><tr/>  
</table>

- A **blue** colored cell means "Uncommitted"
- A **green** colored cell means "Committed"
- A **red** colored cell means "Unplanned"
  
Now you can lookup what the Team is working on during the Sprint and contact them easily based on the information contained in the event.
