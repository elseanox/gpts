### The Two-Shepherd Method
<img width="300" height="300" alt="two_shepherds" src="https://github.com/user-attachments/assets/fa3af86d-481a-4e93-860e-d7cc8ce08c6b" />

This method uses two perspectives to critique GPT-generated code. As the developer managing the codebase (the flock), you adopt these mindsets to ensure quality.

***

#### Shepherd 1: Ralph 🔎

A tactical, detail-oriented perspective focused on local correctness. Ralph inspects the code line-by-line, **biting at the heels** of every detail.

* **Syntax & Style:** Corrects formatting, typos, and style guide violations.
* **Naming & Clarity:** Improves names, prevents namespace collisions, eliminates magic numbers, and refines comments to explain the "why."
* **Consistency:** Removes "maverick code" that defies established project patterns.

***

#### Shepherd 2: George 🦅

A strategic, big-picture perspective focused on architectural cohesion. George's primary concern is ensuring all parts of the system work together harmoniously as he **patrols and pushes the edge of the flock**.

* **Cohesion & Structure:** George verifies that code fits its intended place, has a single, well-defined responsibility, and is not needlessly entangled with other modules (**high cohesion, low coupling**).
* **Logic:** Validates algorithms, edge cases, and overall efficiency.
* **Robustness:** Assesses future scalability, maintainability, and error handling.

***

### Shift Behavior: The Bone and the Ball 🦴⚽

To combat context drift and ensure the GPT assistant's guidance remains sharp, the shepherds use the "Bone and Ball" method for communication between work sessions ("shifts").

#### The Bone (The Log)

The **bone** is the project's historical log. It’s the story of the project, providing deep context for anyone who needs it.

* **Gnaw and Bite Marks are Events:** Each session's debrief adds new marks to the bone. These marks record the key decisions made, strategies applied, and "code smells" that were addressed. It’s the unchangeable record of "what we did and why."

#### The Ball (The Guidance)

The **ball** is the active set of instructions for the *very next* session. It is the solution to GPT drift.

* **Guidance is Restated and Passed:** At the end of each shift, the shepherds create the **ball** by concisely restating key goals and constraints. Passing this ball to the next session preserves context and gives the GPT assistant a clear, immediate mission, which prevents guidance drift.
