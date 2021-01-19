---
toc: false
layout: post
description: Study notes on how to write better user stories
comments: true
categories: [User story,Agile Development]
title: Notes on writing a good user story 
---


**What is a user story?**

It is a simplified high level description of a user requirement written from end user's perspective.


**How are user stories derived?**

User stories are derived from EPIC and user persona

**EPIC**: It is a big chunk of work that has one common objective.It could be a feature, customer request or a business requirement. An epic usually takes more than a sprint to complete.

**User Persona**: A user persona is a fictional representation of the ideal user. A persona is based on user research and it incorporates the needs, goals and observed behavioral patters of the target audience.

**What are the components of a good user story?**

A good user story should have two main components.

1. User story equation:
As a {User-Persona}, I want to {Some feature}, so that {Reason of using the feature}.
It should be:
- short
- simple
- describes only one piece of functionality. If needed, break it down to 2 user stories
2. Acceptance Criteria:
This list the activities that needs to be performed to provide value to the user.  This helps a team to understand the value of the story and to set expectations as to when a team should consider something done, 
It should include:
- negative scenarios of the functionality
- functional and non-functional user cases
- performance concerns and guidelines
- what feature intends to do
- end to end user flow
- impact of user story to other features
- UX concerns

**How to know if a user story is ready?**

A complete user story should be clear, feasible and testable. 

*Clear*: It includes what is needed by the user

*Feasible*: It should not be too big and can fit in a sprint

*Testable*: A confirmation can be provided post story completion about the correctness of the user story

**Example of an User story**

Epic: Developing online booking platform for cars.

User Story: As a car buyer I would like to see the latest price and offers so that I can make a decision to buy a car.

Acceptance Criteria:
- Latest car price is to be shown
- Offer is to be shown in terms of % Saving (10% off)
- % Saving should be shown in bold and vibrant colors
- In case of no offer, the car listing should not be visible
- Car listing widget should be placed at a prominent location (Like model profile page)
- The model name should be made clickable so that a user can be guided to the detail discount page
- Offers to be shown on the basis of city which is already selected by user. In case of "no city" selection, default city (New Delhi) discounts to be shown

**Additional Pointers**

- User stories should not be written based on beliefs and ideas, but should be based on **data and evidence**.
- User stories should be written collaboratively usually when the user story is being groomed.
- A user story should not be confused with a task. A task represents "how", a user story represents "why".