# Adligo.org's Project Management Office (PMO)

## Overview

This is the new home of the Adligo.org Project Management Office.  It is based on [Goolge PMO](https://www.coursera.org/professional-certificates/google-project-management) which you can learn about here;

- [https://www.coursera.org/professional-certificates/google-project-management](https://www.coursera.org/professional-certificates/google-project-management)

The main alteration we have made is to use HTML, Markdown, Open Office and GitHub for everything (Charters, Plans, Kanban Boards, etc).  In addition, we like to keep the projects as small as possible and target one quarter (three months) for our maximum project size.

## Contributing

Contributions are welcome from everyone!  To start, please add yourself to the [https://github.com/adligo/people.adligo.org](https://github.com/adligo/people.adligo.org) project.

## Project Naming Conventions

We use the following naming convention for projects;<br/>
yyyy-q[1-4]-name<br/>
i.e.;<br/>
2026-q1-fab<br/>
2026-q1-slink<br/>
2026-q1-mvpa<br/>
2026-q2-fm<br/>
2026-q2-uits<br/>

The name part can be anything you want. We often use the name of the command line tool, or main-goal we are trying to achieve. 

## Project Structure

Each active project has its own folder under the currently_active folder.  Each project folder must contain a summary and charger file i.e.' <br/>
[2026-q1-fab-summary.md](currently_active/2026-q1-fab/2026-q1-fab-summary.md) <br/>
[2026-q1-fab-charter.md](currently_active/2026-q1-fab/2026-q1-fab-charter.md) <br/>

## Plans

Before starting a project, you should create a plan.  Plans are written in Markdown and stored in the project folder.

[2026-q1-fab-plan.md](currently_active/2026-q1-fab/2026-q1-fab-plan.md) <br/>

## Markdown Kanban Boards

All tasks go into Markdown files in the project folder under the todo, in-progress, and done folders.  Each task should include the creators discord id.  Once tasks are being worked-on they should be moved to the in-progress folder, and the discord id of the people working on the task should be added to the task file.  Once the task is complete, it should be moved to the done folder.

## Templates

- [The Charter Template](templates/CHARTER_TEMPLATE.md)

- [The Project Plan Template](templates/AdligoProjectPlanTemplate.ods)
- [The Project Plan Template with dates collapsed](templates/AdligoProjectPlanTemplateNarrow.ots)

<b>Note: </b> The project plan template is an Open Office spreadsheet that can be exported (saved) to a html file;

i.e. [https://adligo.github.io/pmo.adligo.org/templates/AdligoProjectPlanTemplate.html](https://adligo.github.io/pmo.adligo.org/templates/AdligoProjectPlanTemplate.html)
[https://adligo.github.io/pmo.adligo.org/templates/AdligoProjectPlanTemplateNoEstimatedDates.html](https://adligo.github.io/pmo.adligo.org/templates/AdligoProjectPlanTemplateNoEstimatedDates.html)

We have made some small improvements to the Google Project Management Project Plan template by adding expanding and contracting groups in open office.  This allows us to use the same template for projects without dates (i.e. most of Adligo.org) and projects with dates (i.e. most companies).


## Forks and Pull Requests

Progress-tracking is performed via GitHub forking and pull requests of this repository.

## Archive

At the end of each quarter, we archive the project folder and move it to the archive folder.

## License

[Apache 2.0](LICENSE)
