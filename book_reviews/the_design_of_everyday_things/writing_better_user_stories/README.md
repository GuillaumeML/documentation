# User story example

As a user, I want to hear sound alerts when sending and receiving messages so conversations feel more immediate (and asynchronous).
Acceptance Criteria
- It’s done when the outgoing sound alert is played when a message is sent.
- It’s done when the incoming sound alert is played when a message is received.
Sound Files
Outgoing sound file: http://www....
Incoming sound file: http://www....

## The summary

Story summaries should be structured as follows:

```As [the actor], I want [the something] so I can [the goal].```

Lets break down the individual parts of the structure further.

The actor — the person using the feature.

The something — what the user needs the feature for.

The goal — why the user needs it.

The goal is probably the most important part of the summary as it makes sure you’re solving the right problem. Struggling to write a goal should make you reconsider if the feature is really that important.

## The acceptance criteria

This section is a checklist to confirm the work done on a ticket meets the intended purpose and maps the deliverable into smaller outcomes.

For developers this helps break stories into smaller packets of work. For QA it provides a clear checklist for signing off stories with. Each outcome should start with “It’s done when…”.

## Other descriptions

Mockups and images should be linked (if available). These assets really make a difference for everyone involved in the process.

Technical notes should be included if needed. Try to keep this on the factual side though. I’m not a fan of spoon feeding developers but pointing people in the right direction to existing solutions or ideas will help things get done faster. Comment threads tend to be better for more opinion driven content and clearly shows who added it.

# Bug Ticket example

```Users should be able to select (and apply) the ‘disabled’ filter on the ‘Agents’ page without being redirected to another page.
Scenario
- Log in and navigate to 'Agents' section.
- Select the ‘disabled’ filter button.
Expected result
The agents table should only show ‘disabled’ agents.
Actual result
The user is redirected to another page — this is an undefined ‘Agent’ page.
```

## The summary

The summary should identify what the problem is, the area it occurs and what it’s impacting on. If possible, you should outline the bug from the perspective of the user.

## The scenario

This section should be a roadmap for recreating the bug, a step-by-step account of exactly what was done to find it. This means people can find it, fix it and test it efficiently.

## Expected Result

An ‘expected’ result is what SHOULD happen after the steps outlined in the scenario are followed.

## Actual result

An ‘actual’ result is what IS happening after the steps outlined in the scenario are followed.

## Other Descriptions

For more complex issues, a further summary can be useful. Consider noting previous (or related) issues and any technical aspects.

Remember to include screenshots of the bug in action and any error/console messages where possible. This goes long way to helping everybody understand the issue better.
