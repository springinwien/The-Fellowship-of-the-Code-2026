# The Fellowship Companion - Artifact II: Decisions

## System Capability

**Emergency Alert**

We chose this capability because it solves a key problem in our system: slow communication in dangerous situations.

During the journey, members of the Fellowship can get separated or suddenly face risks. In these moments, it is important to react quickly. The Emergency Alert allows a user to send a signal to the others and ask for help immediately.

## Flow
The flow starts when a Fellowship member notices a dangerous situation.

At this point, the user has to decide whether to send an emergency alert or not. This is the main decision in this feature.

If the user sends the alert, the system shares their location and situation with the rest of the Fellowship. The others receive the alert and try to help. If they react fast enough, help arrives and the situation improves. If they are too late, the risk is still there.

If the user decides not to send the alert, no help is organized and the user has to deal with the situation alone, which increases the danger.

The flow is kept simple on purpose to clearly show the decision and its consequences.

> [Flowchart](https://github.com/GollumGPT/The-Fellowship-of-the-Code-2026/blob/7e07b5e8ce65be18986efaba1d777a36e3982f94/artifacts/artifact-2/src/mermaid.md)

## Wireframe

The wireframe shows a simple emergency screen in the Fellowship Companion.

At the top, the user can see their current situation, including location and risk level. Below that, there are two clear options: sending an emergency alert or not sending one.

There is also a short explanation of what happens if the alert is sent, so the user understands the consequences of their decision.

A status section shows whether an alert has already been sent.

> [Wireframe](https://github.com/GollumGPT/The-Fellowship-of-the-Code-2026/blob/995948b57a70a8225ec2d3838a2cc9155cf3e858/artifacts/artifact-2/src/wireframe.png)

## Design Rationale

The goal of this design is to support quick and clear decision-making in a dangerous situation.

The Emergency Alert helps improve communication and coordination between Fellowship members. This is important because the system should help users stay aligned and react to changing situations.

We focused on one main decision: whether to send an alert or not. This makes the feature easy to understand and fits the goal of Phase 2.

The interface is simple and only shows the most important information. This helps reduce confusion and allows the user to act quickly.

We assumed that the user is under time pressure and does not have much time to think, so the design supports fast and clear actions.

**Assumption:** The user knows what decision they want to make.
