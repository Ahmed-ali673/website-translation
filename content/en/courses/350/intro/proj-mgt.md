---
# Page title
title: Project Management

# Title for the menu link if you wish to use a shorter link title, otherwise remove this option.
linktitle: Project Management

# Page summary for search engines.
summary: Second programming course for MIS majors utilizing Python to build data-driven business applications.

# Date page published
date: 2021-03-23

# Academic page type (do not modify).
type: book

# Position of this page in the menu. Remove this option to sort alphabetically.
weight: 4

draft: False


---

Project management is about ensuring that the project is performed to specification and within time and resource budget. This involves ensuring each team member knows what they are supposed to do.

We will depart from traditional project management and use a more agile approach. The main difference is that with agile development requirements are expected to change and so the team uses tools and works with the exxpectation that requirements can change. The success of such an approach will require that each memeber has initiative and is able to perform some level of self management, such as using the tools put in place to manage the team and is able to select tasks to perform themselves.

We will utilize the boards available on GitHub to manage projects. Each project must start with requirements, including data requirements. Specifically, a Kanban board must be created under the project tab on github, with three columns:
1. To do
2. In Progress
3. Done

## Project Manager's task
1. Create a ticket for each requirement and place them in the To Do column
2. Follow up on tasks in the In Progress column that are delayed and help the memebers comeplete them
3. For tickets in the Done column, the project manager must ensure that the work for that column is merged to the master branch
4. Add a ticket to the To Do list whenever a new feature is requested or a bug is found or a task needs to be completed by the team

## Team memebers' tasks
1. Choose a ticket from the To Do column to work in, by moving it to the In Progress column and assgning the ticket to themselves so the ticket shows their name on it. Memeber should not forget the [workflow]({{< ref "collab.md#our-workflow" >}}) and must create a branch for working on that ticket.
2. Once the work is completed for the ticket, the member must submit a pull request through github to merge the work branch to the master branch. If the pull request was created, then the memeber can move the ticket to the done column.
3. If the member is aware of new features, bugs, or tasks, then they can contribute by adding tickets to the To Do column.

Following this project management process, will make visible for everyone through GitHub the effort each memeber put into the project.