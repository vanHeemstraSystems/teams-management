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
| FLOW: [NAME] |
| --- |
| Task: DESCRIPTION |
| Think It | Speak It | Act | It Happens |
| Make a Decision: (Outcome: Decision) / Solve a Problem: (Outcome: Solution) / Learn a System: (Outcome: Knowledge) | EXPLANATION |
| Planning / Scheduling / Learning/Creating | EXPLANATION |
| Task: DESCRIPTION |
| Think It | Speak It | Act | It Happens |
| Make a Decision: (Outcome: Decision) / Solve a Problem: (Outcome: Solution) / Learn a System: (Outcome: Knowledge) | EXPLANATION |
| Planning / Scheduling / Learning/Creating | EXPLANATION |
| Task: DESCRIPTION |
| Think It | Speak It | Act | It Happens |
| Make a Decision: (Outcome: Decision) / Solve a Problem: (Outcome: Solution) / Learn a System: (Outcome: Knowledge) | EXPLANATION |
| Planning / Scheduling / Learning/Creating | EXPLANATION |
```

A workitem is:

> A task that a participant can process within a collaboration.

Here is an example of **flow-developing-an-internal-security-roadmap.md**:

| FLOW: DEVELOPING AN INTERNAL SECURITY ROADMAP |
| --- |
| Task: Gather existing documentation on the ART's current security framework and organizational strategic goals. |
| Think It | Speak It | Act | It Happens |
| Learn a System: (Outcome: Knowledge) | This involves researching and understanding the current security infrastructure and organizational objectives - clearly a learning activity to comprehend existing systems. |
| Learning/Creating | You're absorbing information from existing materials to build your knowledge base. |
| Task: DESCRIPTION |
| Think It | Speak It | Act | It Happens |
| Make a Decision: (Outcome: Decision) / Solve a Problem: (Outcome: Solution) / Learn a System: (Outcome: Knowledge) | EXPLANATION |
| Planning / Scheduling / Learning/Creating | EXPLANATION |
| Task: DESCRIPTION |
| Think It | Speak It | Act | It Happens |
| Make a Decision: (Outcome: Decision) / Solve a Problem: (Outcome: Solution) / Learn a System: (Outcome: Knowledge) | EXPLANATION |
| Planning / Scheduling / Learning/Creating | EXPLANATION |
