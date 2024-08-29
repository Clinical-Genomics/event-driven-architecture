# Event-driven architecture
This is a repository for project management in the event-driven architecture POC [project](https://github.com/Clinical-Genomics/project-planning/issues/525).

- [Presentation of selected platform: NATS JetStream](https://docs.google.com/presentation/d/1YHi_4m2xAGfqsQzPpU-TIAMdIsSnIBpRzTgw0ePp0kI/edit#slide=id.p)
- [Key considerations](https://github.com/Clinical-Genomics/event-driven-architecture/issues/16)
- [Mapping out existing platforms](https://github.com/Clinical-Genomics/event-driven-architecture/issues/17)
- [Evaluating existing platforms](https://github.com/Clinical-Genomics/event-driven-architecture/issues/18)


## Project summary
Time span 2024-05-02 until 2024-08-02.
What: replace one timer in production with an event.
How: implement a basic pub/sub messaging pattern using the confluent Kafka platform.
Why: evaluate viability of messaging pattern at clinical genomics to reduce turn around times.

@seallard will act as  a facilitator, setting up meetings, planning and ensuring the project moves forward.


## How we work
- Build backlog with user stories
- Separate technical refinement
- Separate sprint planning
- Sprint where we execute the plan
- Sprint retrospective

The user stories are created as milestones [here in this repo](https://github.com/Clinical-Genomics/streamline-delivery/milestones).
The implementation plan is broken down into [work item issues](https://github.com/Clinical-Genomics/streamline-delivery/issues?q=is%3Aopen+is%3Aissue+label%3A%22Work+item%22) which are associated with the milestone.
The sprint starts once the sprint planning is done and lasts for a preset time period (usually two weeks).

## Why we work like this
- Creating user stories increases the likelihood that we build the right thing.
- Creating an implementation plan increases the likelihood we build the thing right.
- Planning the sprints increases the likelihood that we build the things in the right order.
- Having retros increases the likelihood we do not repeat mistakes.

Doing the steps above separately decreases uncertainty about what needs to be done which means we get more things done.

## Creating user stories
### Template for user story
```
Title: A short, descriptive title.

As a [type of user],
I want [an action or feature],
So that [benefit or reason].

Acceptance Criteria
- Criteria 1
- Criteria 2
- Criteria 3
...

Notes
- Additional information.
- Dependencies.
- Related user stories.
```
Each story is assigned a priority based on how important it is to production.

## Technical refinement
The developers prepare for a refinement meeting for a specific user story and discuss the way to implement it.
The decided upon implementation plan is documented and an estimate of the amount work is done.
Separate work item issues are created based on the implementation plan and associated with the story milestone.

## Sprint planning
Based on the dependencies, priority and work estimate, the developers decide on which stories to work on during the sprint.
Individual work items are scheduled for the sprint - put into the ready column on the project board.
Developers are assigned to the user stories and know which work items they should work on.

## Sprint
The developers implement the work items.
If anything is unclear regarding the implementation, a technical refinement is scheduled if necessary.
If anything is unclear regarding the acceptance criteria, a user story meeting is scheduled if necessary.

## Retrospective
Once the sprint is over, the devs meet and
- Go through the project board
- Discuss what went well
- Discuss what could have gone better
- Write down actions to take to improve the next sprint

## Resources
- [Retro notes](https://docs.google.com/document/d/1mY1dSQl9fMe6nuyP09ZAa3y29TGPDyO0dOi16R7kdds/edit?usp=sharing)
- [Project description](https://github.com/Clinical-Genomics/project-planning/issues/525)
