# Teams Management

In order to manage one or more teams, we create a directory on our workspace called "teams".

```
root
├── teams
│   ├── team-[NAME]
│   ├── team-[NAME]
│   ├── team-[NAME]
│   ├── team-[NAME]
│   ├── team-[NAME]
│   ├── team-[NAME]
│   ├── team-[NAME]
│   ├── team-[NAME]
│   └── team-[NAME]
```

For an easy way to create this diagram of a directory tree structure, see [whoisryosuke/markdown-directory-tree.md](https://gist.github.com/whoisryosuke/813186b07e6c9e4d23593041827a6530)

A team is:

> A number of persons associated together in work or activity.

An example of a team name is **Team Security**.

Inside of a team directory (```team-[NAME]```), we list the following:

```
root
├── teams
│   ├── team-[NAME]
│   ├── team-[NAME]
│   ├── team-[NAME]
│   ├── team-[NAME]
│   ├── team-[NAME]
│   ├── team-[NAME]
│   ├── team-[NAME]
│   ├── team-[NAME]
│   └── team-[NAME]
│       └── flows
│           ├── flow-[NAME]
│           ├── flow-[NAME]
│           └── flow-[NAME]
│               ├── flow-[NAME].md
│               └── ...
```

A flow is: 

> Work items that are connected together in a defined sequence. 

An example of a flow is **Developing An Internal Security Roadmap**.

The markdown file of ```flow-[NAME].md``` contains a table in which all workitems are listed in a chronological order (from top to bottom), like so:

```
| <td colspan=5>FLOW: [NAME]</td> |
| <td colspan=5>---</td> |
| | <td colspan=4>Task: DESCRIPTION</td> |
| | Think It | Speak It | Act | It Happens |
| Make a Decision:<br/>(Outcome: Decision) / Solve a Problem:<br/>(Outcome: Solution) / Learn a System:<br/>(Outcome: Knowledge) | <td colspan=4>EXPLANATION</td> |
| Planning: / Scheduling: / Learning/Creating: | <td colspan=4>EXPLANATION</td> |
| | <td colspan=4>Task: DESCRIPTION</td> |
| | Think It | Speak It | Act | It Happens |
| Make a Decision:<br/>(Outcome: Decision) / Solve a Problem:<br/>(Outcome: Solution) / Learn a System:<br/>(Outcome: Knowledge) | <td colspan=4>EXPLANATION</td> |
| Planning: / Scheduling: / Learning/Creating: | <td colspan=4>EXPLANATION</td> |
| | <td colspan=4>Task: DESCRIPTION</td> |
| | Think It | Speak It | Act | It Happens |
| Make a Decision:<br/>(Outcome: Decision) / Solve a Problem:<br/>(Outcome: Solution) / Learn a System:<br/>(Outcome: Knowledge) | <td colspan=4>EXPLANATION</td> |
| Planning: / Scheduling: / Learning/Creating: | <td colspan=4>EXPLANATION</td> |
```

A workitem is:

> A task that a participant can process within a collaboration.

Here is an example of **flow-developing-an-internal-security-roadmap.md**:

<table>
  <tr>
    <th colspan=5 text-align=center>FLOW: DEVELOPING AN INTERNAL SECURITY ROADMAP</th>
  </tr>
  <tr>
    <td></td><td colspan=4>Task: Gather existing documentation on the ART's current security framework and organizational strategic goals.</td>
  </tr>
  <tr>
    <td></td><td>Think It</td><td>Speak It</td><td>Act</td><td>It Happens</td>
  </tr>
  <tr>
    <td>Learn a System: (Outcome: Knowledge)</td><td colspan=4>This involves researching and understanding the current security infrastructure and organizational objectives - clearly a learning activity to comprehend existing systems.</td>
  </tr>
  <tr>
    <td>Learning/Creating:</td><td colspan=4>You're absorbing information from existing materials to build your knowledge base.</td>
  </tr>
  <tr>
    <td></td><td colspan=4>Task: Outline your 'Securing the Foundation' approach, identifying key priorities, risks, and resources required.</td>|
  </tr>
  <tr>
    <td></td><td>Think It</td><td>Speak It</td><td>Act</td><td>It Happens</td>
  </tr>
  <tr>
    <td>Make a Decision:<br/>(Outcome: Decision)</td><td colspan=4>You're determining which security elements to prioritize, what risks matter most, and how to allocate resources - all decision-making activities.</td>
  </tr>
  <tr>
    <td>Planning:</td><td colspan=4>You're developing a strategic approach and identifying key elements for implementation.</td>
  </tr>
  <tr>
    <td></td><td colspan=4>Task: Develop a preliminary timeline with phases or your roadmap.</td>
  </tr>
  <tr>
    <td></td><td>Think It</td><td>Speak It</td><td>Act</td><td>It Happens</td>
  </tr>
  <tr>
    <td>Make a Decision: (Outcome: Decision)</td><td colspan=4>Creating a timeline requires deciding on sequence, duration, and importance of different security initiatives.</td>
  </tr>
  <tr>
   <td>Planning</td><td colspan=4>You're establishing the sequence and duration of activities in your security initiative.</td>
  </tr>
</table>
