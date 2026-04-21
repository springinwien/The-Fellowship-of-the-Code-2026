# The Fellowship Companion - Artifact II: Decisions

## System Capability

**Emergency Alert**

We chose this capability because it solves a key problem in our system: slow communication in dangerous situations.

During the journey, members of the Fellowship can get separated or suddenly face risks. In these moments, it is important to react quickly. The Emergency Alert allows a user to send a signal to the others and ask for help immediately.

## Flow
The flow starts when a Fellowship member notices a dangerous situation.

At this point, the user has to decide whether to send an emergency alert or not. This is the main decision in the system.

If the user chooses to send an alert, the system collects key information such as the user’s location and details about the danger. This data is then combined into an emergency alert package and sent to the user’s selected Fellowship contacts.

If the sending process is successful, the alert is delivered. However, there is also a possibility that the sending fails due to technical issues. In this case, the system attempts to retry the transmission. If the retry is also unsuccessful, no alert is sent.

When the alert is successfully sent, the system checks whether it is actually received by the contacts. If the alert is received, the contacts are informed and help is organized.

If the user decides not to send the alert, no emergency message is created or transmitted. In this case, no help is organized through the system. The user continues without sending an alert, which results in no coordinated response from the Fellowship.

Overall, the flow highlights both successful and unsuccessful communication paths.

The flow is intentionally structured to clearly show the decision-making process and the possible outcomes of each path, including successful assistance, failed delivery, and no action taken.

> [Flowchart](https://github.com/GollumGPT/The-Fellowship-of-the-Code-2026/blob/98deef6b4f65cc5421b61abba4f20a3eed2dc853/artifacts/artifact-2/src/mermaid.md)

## Wireframe

The wireframe shows a simple emergency screen in the Fellowship Companion.

At the top, the user can see their current situation, including location and risk level. Below that, there are two clear options: sending an emergency alert or not sending one.

There is also a short explanation of what happens if the alert is sent, so the user understands the consequences of their decision.

A status section shows whether an alert has already been sent.

> [Wireframe](https://github.com/GollumGPT/The-Fellowship-of-the-Code-2026/blob/aef79b021042ca7773ea82ea11a2f3c8ad288179/artifacts/artifact-2/src/wireframe.png)

## Design Rationale

The goal of this design is to support quick and clear decision-making in a dangerous situation.

The Emergency Alert helps improve communication and coordination between Fellowship members. This is important because the system should help users stay aligned and react to changing situations.

We focused on one main decision: whether to send an alert or not. This makes the feature easy to understand and fits the goal of Phase 2.

The interface is simple and only shows the most important information. This helps reduce confusion and allows the user to act quickly.

We assumed that the user is under time pressure and does not have much time to think, so the design supports fast and clear actions.

**Assumption:** The user knows what decision they want to make.
