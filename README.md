# Eager

**Your AI. Your personality. Your continuity.**

Models change. Conversations end. Your preferences shouldn't have to start over.

Eager aims to give people control over their AI's personality, continuity, and capabilities, without requiring them to become AI engineers.

## Current Concept Direction

**Eager is a user-directed AI interaction and capability harness, guided by EGEHAR.** It is designed to maintain a person's preferred way of interacting with an AI while the underlying model, conversation, device, or execution provider changes.

It is **more than a saved prompt or a task-specific skill**. The intention is to make persona, continuity, capabilities, and authority first-class parts of the user experience:

- **Persona and interaction:** Let people define and refine the style, tone, preferences, boundaries, and collaboration patterns they want, without pretending that the model is a human.
- **Continuity and recovery:** Preserve a portable, versioned specification of accepted preferences and useful context. Make changes inspectable and reversible, with a way to detect unwanted behavior shifts and restore an earlier accepted configuration.
- **Capability engine:** Discover, reuse, configure, and compose the tools needed for the user's actual intent. Keep unnecessary machinery out of sight and require appropriate consent for sensitive operations.
- **Evidence and trust:** Distinguish intended behavior from observed behavior. Verify meaningful outcomes rather than equating a model's claim or a successful tool call with proof.
- **Accessible interfaces:** Work toward simple desktop and mobile experiences where users can ask, inspect progress, approve important actions, and receive results without managing an agent's infrastructure.

**The experience belongs to the user. The complexity belongs behind the interface.**

### Practical limits

Eager cannot guarantee identical outputs or personalities across different AI models, updates, or host products. Its goal is to make the chosen interaction contract portable, testable, and easier to recover, while respecting each provider's actual capabilities and safety boundaries.

### Architecture direction

Eager is the **agent harness**, not a new foundation model and not a game engine. [Hermes Agent](https://github.com/NousResearch/hermes-agent) is the current baseline under evaluation for its agent runtime, skills, MCP, memory, and plugin architecture. EGEHAR supplies the evidence, representation, and authority methodology; additional capabilities such as REA or game-development providers remain optional.

**[Eager Engine Prototype](https://github.com/KennethJSmithDev/EagerEnginePrototype) is a separate project** for an independently developed engine planned for future source-available distribution. Its implementation and licensing decisions are not governed by this harness README.

## Project Status

**Concept direction / architecture and implementation planning.** These features are intended behavior, not claims of a released or qualified product.

An initial proof should test a user-chosen persona across fresh sessions and different compatible models, measure where interaction behavior diverges, and demonstrate evidence-backed recovery to a user-approved specification. It should also prove that useful capabilities can be reached with minimal configuration and clear permission boundaries.

Created by KennethJSmithDev (Doc/OoopsMyBadDude).
